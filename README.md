# obsidian-header-level-icons

Header level icons provide a visual indicator of the header level. This is useful to understand the structure of 
your document when editing.

This is a pure CSS implementation, no JavaScript is used.

## Before

![](screenshot-before.png)

## After

![](screenshot-after.png)

## How to install

Save the [header-level-icons.css](https://raw.githubusercontent.com/codewithcheese/obsidian-header-level-icons/main/header-level-icons.css) file to your computer.

Copy the css file into your vaults configuration folder. If your not sure where that is, follow the instructions in [Obsidian configuration folder docs](https://help.obsidian.md/Files+and+folders/Configuration+folder).

Enable the snippet in Settings -> Appearance. See the [Obsidian CSS snippets docs for instructions.](https://help.obsidian.md/Extending+Obsidian/CSS+snippets)

For mobile, you will need to sync the snippet from your desktop vault and then enable it in your mobile settings.

## How it works

Uses a `::before` selector to add a SVG background in place of the header fold icon.

Sets the header icon to be transparent so that it can still be clicked on.

When the header is folded it is rotated 90deg and made darker.
