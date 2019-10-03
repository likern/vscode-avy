# VSCode-Avy

<p align="center">
  <img width="559" height="397" src="/demo/poster.png" >
</p>

> Inspired by [Emacs Avy](https://github.com/abo-abo/avy) package.

![Usage demo](/demo/demo.gif?raw=true "Usage demo")

## Getting Started

Bind the following keyboard shortcuts and you'll be ready to start using the extension: 

- `findThenJump.initiate`: Starts a jump-search without text selection.
- `findThenJump.initiateWithSelection`: Jump to a search term, selecting all text between the current cursor position and the search term.

> ℹ️ No default keybindings are provided by this extension - you'll have to bind the commands yourself.

## Theming

You can customize the colors of the text decorations that are displayed left of each text match by adding the following settings to `settings.json`:

- `findThenJump.textDecorationForeground`: Controls text color of the text decoration.
- `findThenJump.textDecorationBackground`: Controls the background color of the text decoration.

Example `settings.json`:

```json
{
    "workspace.colorCustomizations": {
        "findThenJump.textDecorationForeground": "#FFFFFF",
        "findThenJump.textDecorationBackground": "#000000"
    }
}
```

## Bugs & Suggestions

Feel free to create an [issue](https://github.com/likern/vscode-avy/issues)
outlining the bug or suggestion!

## Change Log

[See here.](CHANGELOG.md)

## Copyright

Typewriter icon made by [Freepik](https://www.freepik.com),
from [FlatIcon](https://www.flaticon.com),
under a **Flaticon Basic License**.
