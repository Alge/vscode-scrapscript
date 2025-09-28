# ScrapScript for VS Code

Syntax highlighting support for ScrapScript (.scrap) files in Visual Studio Code.

## Features

- Syntax highlighting for ScrapScript language constructs
- Comment support with `--`
- Auto-closing brackets and quotes
- File association for `.scrap` files

## Installation

1. Clone this repository
2. Run `npm install -g vsce` to install the VS Code Extension CLI
3. Run `vsce package` to create the extension package
4. Install with `code --install-extension scrapscript-syntax-*.vsix`

## Development

To work on this extension:

1. Clone the repository
2. Open in VS Code
3. Press F5 to launch a new Extension Development Host window
4. Open a `.scrap` file to test syntax highlighting

## License

MIT