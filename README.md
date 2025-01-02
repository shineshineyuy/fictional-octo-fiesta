# Start Data API Builder

A Visual Studio Code extension that adds a quick way to start Data API Builder directly from `dab-config.json`.

![](https://github.com/JerryNixon/data-api-builder-vscode-ext/raw/HEAD/images/screenshot.png)

## Features

- Adds a right-click context menu for files named `dab-config.json`.
- Automatically opens a new terminal and runs `dab start`.

## Requirements

- Ensure that `dab` is installed: `dotnet tool install microsoft.dataapibuilder -g`

## Known Issues

- Only files named exactly `dab-config.json` will show the context menu option.
- The terminal assumes `dab` is available globally in your environment.

## Release Notes

### 1.0.0

- Initial release: Context menu and terminal support for starting DAB.