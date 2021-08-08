# panini-vscode Extension

Provides syntax highlighting for the Panini programming language.

## Install from Visual Studio Code Marketplace
1. Search for Panini in the Extensions tab, look for extension published by `hemalpatil` and install.

## Installation from source
1. Clone the repository from `https://github.com/HemalPatil/panini-vscode` and compile the extension.
```
$ npm install -g vsce
$ vsce package
```
2. Go to extension tab of Visual Studio Code and choose 'Install from VSIX' from the hamburger menu.
3. Navigate to compiled `.vsix` file and install it.
4. Reload Visual Studio Code if required.
5. The extension is activated for files with `.ण` and `.panini` extension.