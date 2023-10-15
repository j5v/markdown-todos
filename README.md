CSS for your Markdown documents in VSCode, to indicate the status of items in your nested todo lists.

For basic usage, place `<todo>` tags at the beginning of your item text, and progress them through yellow `<wip>`, then green `<done>` states.

![A nested todo list, where each item has a background styled to match the state of the item. All done items are dark green, all work-in-progress items are yellow, and all todo items are dark red. Each item also contains extra text from the CSS, with the word "DONE", "WIP", or "TODO", which might be read by a screen reader.](docs/simple-todo.png)

# How to install

To affect only the current Markdown preview, paste the custom CSS into a `<style>` tag in the Markdown source.

To affect all Markdown previews in the current VSCode workspace, or for all VSCode workspaces:
1. Select **File** > **Preferences** > **Settings**.
2. Type **Style** in the settings filter.
3. Select **User** to affect all workspaces, or **Workspace** to affect the current workspace.
4. Select **Extensions** > **Markdown** from the settings categories.
5. In the **Markdown: Styles** setting, add the location of your CSS file.

# Customization hints

You can style existing HTML tags rendered by Markdown preview.

You can use custom tags and attributes with CSS.

## Markup vs Markdown

Markdown source can ideally be read by humans. It's easy to customize tags and styles, to make the Markdown source hard to read. That might be fine if you're writing for yourself.
