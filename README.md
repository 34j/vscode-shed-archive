# VSCode Extension for shed

[![GitHub](https://img.shields.io/github/license/34j/vscode-shed?logo=github&logoColor=%23181717)](https://github.com/34j/vscode-shed)
[![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/mikoz.shed?logo=visual-studio-code&logoColor=%23007ACC)](https://marketplace.visualstudio.com/items?itemName=mikoz.shed)
[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/mikoz.shed)](https://marketplace.visualstudio.com/items?itemName=mikoz.shed)

VSCode extension for [shed](https://github.com/Zac-HD/shed).

[![Install Now](https://img.shields.io/badge/-Install%20Now-107C10?style=for-the-badge&logo=visualstudiocode)](https://marketplace.visualstudio.com/items?itemName=mikoz.shed)

Consider using [Composite Formatter](https://marketplace.visualstudio.com/items?itemName=mikoz.composite-formatter) to run multiple formatters at once as a single formatter.

## Requirements

1. VS Code 1.64.0 or greater
1. Python 3.7 or greater
1. node >= 14.19.0
1. npm >= 8.3.0 (`npm` is installed with node, check npm version, use `npm install -g npm@8.3.0` to update)
1. Python extension for VS Code

## Extension Settings

|Name|Description|
|----|-----------|
|`shed.logLevel`| The log level the extension logs at, defaults to 'error'.|
| `shed.args`| Additional arguments passed in. Each argument is a separate item in the array.|
| `shed.path`| When set to a path to shed binary, extension will use that. NOTE: Using this option may slowdown server response time.|
| `shed.importStrategy`| Defines where `shed` is imported from. This setting may be ignored if `shed.path` is set.|
| `shed.interpreter`| When set to a path to python executable, extension will use that to launch the server and any subprocess.|
| `shed.showNotification`| Controls when notifications are shown by this extension.|

## Extension Commands

`shed: Restart Server`: Restart Server.

<!--## Known Issues-->