CSS for your Markdown documents in VSCode, to indicate the status of items in your nested todo lists.

For basic usage, place `<todo>` tags at the beginning of your item text, and progress them through yellow `wip`, then green `done` states.

# How to install

To affect only the current Markdown preview, add the custom CSS into a `<style>` tag in the Markdown source.

To affect all Markdown previews in the current VSCode workspace, or for all VSCode workspaces:
1. Select **File** > **Preferences** > **Settings**.
2. Type **Style** in the settings filter.
3. Select **User** to affect all workspaces, or **Workspace** to affect the current workspace.
4. Select **Extensions** > **Markdown** from the settings categories.
5. In the **Markdown: Styles** setting, add the location of your CSS file.