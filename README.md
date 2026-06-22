# Basic VS Code project for Ethos DevTools

## Installation

From a new project (empty folder) or from an existing project, run the command palette, `Scaffold Ethos DevTools project`, and follow the instructions. This will create a basic project with a sample sensor and a sample telemetry CSV file.

## Code completion and type checking

After having setup the project, install the recommended [sumneko.lua](https://marketplace.visualstudio.com/items?itemName=sumneko.lua) extension and using the command palette, `Lua: Open Addon manager...`, install the Ethos definitions, this will give you code completion and type checking for the Ethos API. Update the addon after each new release of ETHOS.

>Note:If the extension is already installed, included .vscode/settings.json will enable it automatically.

## Simulator setup

If the ethos taskbar does not appear, with the command palette, run `Ethos: Show Menu`, otherwise, simply click on the statusbar and choose `Deploy and launch SIM`. You will have on first start a storage error, disregard it and click OK.
You can then try to `Play Telemetry`.

## Additional information

Refer to the [Ethos DevTools documentation](https://github.com/flyingeek/vscode-ethos-devtools/blob/main/README.md) for more information on how to use the tools and develop your project.

You can also check the [Ethos Lua Definitions](https://github.com/flyingeek/vscode-ethos-devtools/blob/main/ETHOS_LUA_DEFINITIONS.md) for alternative setup if you want AI to access it from your workspace folder.
