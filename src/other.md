## Other
- Hidden inline: <hide>hidden</hide> with non-hidden content after.
- <now>Working on this now
- <ti>1234</ti> Story code
- <tid>0010</tid> Defect code
- <tic>0099</tic> Clarification code
- <blocker>Blocker</blocker>
- Mention user <tag>j5v


<style>
  li { margin-bottom: 0.1rem }

  now {
    display: block;
    padding: 2px 8px;
    margin-left: -0.6rem;
    box-shadow: 0px 0px 9px 4px hsla(60,100%, 50%, 1);
  }

  /* ticket numbers */
  ti, tid, tic {
    padding: 0rem 0.4rem 0.1rem 0.4rem;
    background: hsla(120,80%,90%,0.2);
    color: hsla(120,0%,100%,0.80);
    font-weight: 400;
    margin-right: 0.25em;
    border: 1px solid hsla(120,80%,90%,0.2);
    border-radius: 4px;
    letter-spacing: 0.06rem;
    white-space: nowrap;
    line-height: 1.9em;
  }
  tid { background: hsla(0,80%,85%,0.32) }
  tic { background: hsla(180,90%,90%,0.32) }

  /* blocker tag */
  blocker {
    color: #FEE;
    background-color: #E00;
    padding: 2px 5px;
    margin: 0px 2px 0px 0px;
    border-radius: 4px;
  }
  blocker:hover:after {
    margin-left: 1rem;
    content: 'BLOCKED'
  }

  hide { display: none; }

  tag {
    background-color: hsla(0,0%,100%,0.05);
    border-radius: 10rem;
    padding: 0.1rem 0.6rem;
    margin-left: 0.3rem;
    color: hsla(0,100%,80%,1);
    font-weight: 800;
    border: 1px solid hsla(0,0%,100%,0.05);
    box-shadow: 0px 0px 8px hsla(0,100%,90%,0.7);
  }

  /* Fix some table rendering */
  td { vertical-align: top; }
  th { white-space: nowrap; } /* You might not want this */

  /* Compact progress bars */
  progress { width: 3rem; }  

</style>