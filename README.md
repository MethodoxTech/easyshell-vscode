# EasyShell (Syntax Highlight)

Version: 0.0.3

EasyShell syntax highlighting for `.easy` files for Visual Studio Code.

EasyShell uses PowerShell-compatible syntax highlighting.

## EasyShell

For EasyShell source and binaries, visit [source page on GitHub](https://github.com/MethodoxTech/EasyShell).

Release: [Downloads](https://github.com/MethodoxTech/EasyShell/releases) (Current version: [v0.1.0](https://github.com/MethodoxTech/EasyShell/releases/tag/v0.1.0)).

## Extension Development

### To Publish

```pwsh
vsce package
```

### To Test

```pwsh
code --new-window --extensionDevelopmentPath="$(pwd)" .   
```

### Notes

For markdown code block fence syntax highlight, `syntaxes\easy-markdown.injection.json` only affects Markdown editor tokenization. The Markdown preview renderer has its own highlighting pipeline, so editor highlighting and preview highlighting are not always identical. VS Code’s Markdown snippets are also separate; adding `easy` to aliases does not necessarily add it to the built-in fenced-code snippet dropdown.

## Changelog

* v0.0.1: Initial setup.
* v0.0.2: Markdown code fence block syntax support.
* v0.0.3: Update README; Add links to EasyShell source.

## Links

* [VS Code Extension](https://marketplace.visualstudio.com/items?itemName=Methodox.easyshell)