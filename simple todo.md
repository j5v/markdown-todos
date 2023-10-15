# Category
- <done>Thing
- <wip>Another thing
	-	Part 1
	- Part 2
- <todo>Last thing
- <todo>Really the last thing


<style>
  todo, wip, done { display: block; margin-left: -1.6rem; margin-bottom: 0.1rem; padding: 0.2rem 0.5rem 0.2rem 1.5rem; border-radius: 0.3rem; }

  todo { background-color: hsla(000,50%,20%,0.50); color: hsl(000,50%,80%)  }
  todo:before { content: 'TODO'; float: right; opacity: 0.6 }

  wip { background-color: hsla(60,60%,30%,0.50); color: hsl(60,50%,80%)  }
  wip:before { content: 'WIP'; float: right; opacity: 0.6 }

  done { background-color: hsla(120,10%,20%,0.50); color: hsl(120,10%,80%)  }
  done:before { content: 'DONE'; float: right; opacity: 0.6 }
</style>