# Basic VS Code project for Ethos DevTools

## Installation

From a new project (empty folder) or from an existing project, run the command palette, `Scaffold Ethos DevTools project`, and follow the instructions. This will create a basic project with a sample sensor and a sample telemetry CSV file.

## Code completion and type checking

After having setup the project, install the recommended `sumneko.lua` extension and using the command palette, `Lua: Open Addon manager...`, install the Ethos definitions, this will give you code completion and type checking for the Ethos API. Update the addon after each new release of ETHOS.

## Simulator setup

If the ethos taskbar does not appear, with the command palette, run `Ethos: Show Menu`, otherwise, simply click on the statusbar and choose `Deploy and launch SIM`. You will have on first start a storage error, disregard it and click OK.
You can then try to `Play Telemetry`.
