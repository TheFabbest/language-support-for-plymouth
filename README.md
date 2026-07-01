# Plymouth Language Support

This extension adds language support for Plymouth scripts in Visual Studio Code.
It is unofficial and is not affiliated with the Plymouth project.

## Features

- Syntax highlighting for Plymouth scripts
- Basic snippets for common Plymouth commands
- Support for comments (#, //, and /* */)
- Bracket matching and auto-closing pairs

## Usage

Open a file with the .plymouth or .script extension, or select the Plymouth language manually from the VS Code status bar.

## Requirements

VS Code version 1.85.0 or higher is required.

## Development

To build a VSIX package locally, run:

```bash
npm run package
```

You can then install the generated .vsix file in VS Code by selecting "Install from VSIX..." in the Extensions view.
Alternatively, you can run the extension in a development environment by pressing F5 in VS Code.

## Contributing
This project is open for contributions and beginners are welcome. If you would like to contribute, please fork the repository and submit a pull request with your changes. If you find any issues or have suggestions for improvements, please open an issue in the repository.

## Release Notes

### 0.1.0

Initial public-ready release with improved metadata, packaging support, and documentation.