## What is OverBind?
A utility that allows binding keyboard buttons to virtual Xbox360 controller joystick outputs. Makes use of [ViGEmBus](https://github.com/nefarius/ViGEmBus/) and [ViGEmClient](https://github.com/CasualX/vigem-client). Keybinds are easily customizeable within the app's UI.

Built specifically with Hollow Knight speedruns in mind.

Note: this is for Windows only.

## How to Install
First, you must install the [ViGEmBus driver](https://github.com/nefarius/ViGEmBus/releases). This is necessary for the controller emulation to function.

Then install and run the OverBind installer from the [Releases page](https://github.com/cjonas1999/OverBind/releases).

## How to Compile from Source

Install Tauri CLI

```bash
npm install --save-dev @tauri-apps/cli
```

Install Tauri JavaScript Library

```bash
npm install @tauri-apps/api
```

Start the development server

```bash
npm install
npm run tauri dev
```
