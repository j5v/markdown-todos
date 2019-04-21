# Style sheet demo

## Todo list
- <todo>Action point `todo`
- <wip>Work-in-progress `wip`
  - sub-items: contained by parent
  - <todo>sub-item with `todo` tag
  - <wip>sub-item with `wip` tag
  - <park>sub-item with `park` tag
  - <nodo>sub-item with `nodo` tag
  - <done>sub-item with `done` tag
- <park>Park (do later) `park`
- <info>Item with `info` tag
- <nodo>Won't do `nodo`
- <done>Done `done`
- <todo><c>Compacted list `c`. After first line is hidden
  - hidden sub-item.
- Item without tags
1. Numbered

## Priority tags
- `<o p1>`<o p1>
- `<o p2>`<o p2>
- `<o p3>`<o p3>
- `<o p4>`<o p4>
- `<o AB>` custom content<o p>AB

## Star tags 1..5
- `<o s1>`<o s1></o>
- `<o s2>`<o s2></o>
- `<o s3>`<o s3></o>
- `<o s4>`<o s4></o>
- `<o s5>`<o s5></o>

## Other styling
- hidden inline: <hide>hidden</hide> with non-hidden content after.
- <blocker>This is a blocker</blocker> `blocker`
- Link [here](http://example.com)
- <wip><now>Highlighted with inline `now`
- Progress bar `progress` 0.8<progress value="0.8">
- <ti>1234</ti> Story code `ti`
- <tid>0010</tid> Defect code `tid`
- <tic>0099</tic> Clarification code `tic`
- Mention a user with `tag` <tag>JV
- <up>Review positive `up`
- <down>Review negative / warning `down`
- Code `inline code`
- Formatted code block
  ```JS
  const formattedCode = (par) => (returnValue);
  ```

# h1
## h2
### h3
