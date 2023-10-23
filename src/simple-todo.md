# Simple todo
- <t d>Item
- <t w>Another item
	-	<t d>Part 1
	- <t w>Part 2
	- <t t>Part 3
- This has no tags
- <t t>Last item


<style>
  /* Done: <t d> or <done>, WIP:  <t w> or <wip>, todo: <t t> or <todo> */
  :root {
    --hue-todo: 0;
    --hue-wip: 60;
    --hue-done: 120;
  }

  t, todo, wip, done {
    display: block;
    margin-left: -1.6rem;
    margin-bottom: 0.1rem;
    padding: 0.2rem 0.5rem 0.2rem 1.5rem; border-radius: 0.3rem;
  }
  t:before, todo:before, wip:before, done:before {
    float: right;
    opacity: 0.6;
  }

  t[t], todo { 
    background-color: hsla(var(--hue-todo),50%,20%,0.50);
    color: hsl(var(--hue-todo),50%,80%)
  }
  t[t]:before, todo:before {
    content: 'TODO';
  }

  t[w], wip { 
    background-color: hsla(var(--hue-wip),60%,30%,0.50);
    color: hsl(var(--hue-wip),50%,80%)
  }
  t[w]:before, wip:before {
    content: 'WIP';
  }

  t[d], done { 
    background-color: hsla(var(--hue-done),10%,20%,0.50);
    color: hsl(var(--hue-done),10%,80%)
  }
  t[d]:before, done:before {
    content: 'DONE';
  }
</style>