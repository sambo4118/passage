# PassageJS Syntax Highlighting

Beautiful syntax highlighting for PassageJS interactive fiction files (`.psg`) in Visual Studio Code.

## What is PassageJS?

PassageJS is a powerful alternative to Twine and RenPy for creating interactive fiction and visual novels. It features:

- **Markdown-based** writing with custom extensions
- **Smart linking** with direct links, relative links, and random group selection
- **Built-in animations** like wiggle, typewriter, fade-in, and delayed reveals
- **Transition system** for smooth narrative flow
- **Zero dependencies** - pure vanilla JavaScript

## Features

This extension provides comprehensive syntax highlighting for:

- **Custom macros** - `<<typewriter>>`, `<<onclick>>`, `<<hop>>`, `<<bgcolor>>`, etc.
- **Passage links** - `[[link text|path/to/passage]]` and `[[goto|group/*]]`
- **Markdown formatting** - bold, italic, headings, lists
- **Nested structures** - properly highlights macros within links and other macros
- **Macro attributes** - `<<onclick text="click me">>`, `<<bgcolor color='#1f1f1f'>>`

### Syntax Example

```passage
<<bgcolor color='#1f1f1f'>>
# Welcome to PassageJS!

<<typewriter speed="20">>
This is an example passage with custom animations.
<</typewriter>>

<<onclick>>
Click to reveal hidden content!
<</onclick>>

[[Continue the story|chapter1/intro]]
[[Random encounter|encounters/*]]
```

## Installation

1. Open VS Code
2. Press `Ctrl+P` (or `Cmd+P` on Mac)
3. Type: `ext install sambo4118.passage`
4. Press Enter

Or search for "PassageJS" in the Extensions view (`Ctrl+Shift+X`).

## Usage

The extension automatically activates for files with the `.psg` extension. Just create or open any `.psg` file and start writing!

## Requirements

No dependencies or additional setup required. Just install and use!

## Contributing

Found a bug or want to suggest a feature? Visit the [GitHub repository](https://github.com/sambo4118/passage) to open an issue or submit a pull request.

## Release Notes

### 0.0.1

Initial release of PassageJS syntax highlighting:
- Full macro syntax support
- Passage link highlighting
- Markdown formatting
- Nested structure support
- Attribute parsing for macros

---

**Enjoy writing interactive fiction with PassageJS!** 📖✨

## Working with Markdown

You can author your README using Visual Studio Code. Here are some useful editor keyboard shortcuts:

* Split the editor (`Cmd+\` on macOS or `Ctrl+\` on Windows and Linux).
* Toggle preview (`Shift+Cmd+V` on macOS or `Shift+Ctrl+V` on Windows and Linux).
* Press `Ctrl+Space` (Windows, Linux, macOS) to see a list of Markdown snippets.

## For more information

* [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
* [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

**Enjoy!**
