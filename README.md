# markdown-todos
CSS for your Atom+Markdown lists.

This CSS gives you a visual hint of the status of items in your nested todo lists.

For basic usage, place `<todo>` tags at the beginning of your item text, and progress them through yellow `wip`, then green `done` states. Feel free to make your own CSS if you have difficulty distinguishing the colors I have chosen here.

Other tags have been styled to assist with common software development tasks - see the preview below.

# You will need
- Atom editor
- markdown-preview-plus package

# How to install
Open the `add to styles.less` file, and paste its contents into your `styles.less` file (found in Atom's menu: File > Stylesheet...).

Alternatively, you can paste it into an `.md` file, inside a `<style>` tag, but we recommend the `styles.less` method above.

# What it looks like
![preview](example-preview.png)

# Expected use

This is not intended to replace job management tools (like Trello, Jira, and ServieNow Agile), but it can be helpful for ad-hoc todo lists, lists that are very fluid, or lists of quick todos.
