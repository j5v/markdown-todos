## Priority tags
- Priority 1<o p1>
- Priority 2<o p2>
- Priority 3<o p3>
- Priority 4<o p4>
- Custom content<o p>AB

## Star tags 1..5
- no stars<o s>
- 1 star<o s1>
- 2 stars<o s2>
- 3 stars<o s3>
- 4 stars<o s4>
- 5 stars<o s5>


<style>
  li { margin-bottom: 0.1rem; }
  o {
    float: right;
    min-width: 0.6rem;
    padding: 0.0rem 0.4rem;
    display: inline-block;
    font-weight: 800;
    color: black;
    border-radius: 0.3rem;
    background-color: hsla(120, 0%, 80%, 0.70);
    text-shadow: 0 0 18px white;
  }

  /* p = priority tags */
  o[p1] { background-color: hsla(0, 100%, 70%, 1.0); }
  o[p2] { background-color: hsla(0, 100%, 80%, 0.8); }
  o[p3] { background-color: hsla(0, 100%, 90%, 0.5); }
  o[p4] { background-color: hsla(0, 100%, 95%, 0.4); }
  o[p1]:before { content: '1'; }
  o[p2]:before { content: '2'; }
  o[p3]:before { content: '3'; }
  o[p4]:before { content: '4'; }

  /* s = star tags */
  o[s1], o[s2], o[s3], o[s4], o[s5], o[s], o[s0] {
      background-color: hsla(60, 100%, 50%, 0.18);
      color: hsla(60, 100%, 50%, 1);
      text-shadow: 0 0 13px yellow;
  }
  o[s]:before, o[s0]:before {
    content: '\2605';
    visibility: hidden;
  }
  o[s1]:before { content: '\2605'; }
  o[s2]:before { content: '\2605\2605'; }
  o[s3]:before { content: '\2605\2605\2605'; }
  o[s4]:before { content: '\2605\2605\2605\2605'; }
  o[s5]:before { content: '\2605\2605\2605\2605\2605'; }
</style>