# ADOJAS
[Chinese Version](README_cn.md)
[How to play(EN/CN)](HOWTOPLAY_ALL.md)
## Info
A lite ADOFAI level player.

## Recommended IDE Setup
[Node.js](https://nodejs.org/zh-cn)
[Visual Studio Code](https://code.visualstudio.com/)
[Rust](https://www.rust-lang.org/)
[Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) 
[rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)
[Turbowarp](https://turbowarp.org/desktop)

## Necessary preparations
Before starting,you need:

### A Package Manager(npm,yarn,pnpm) (Recommended: pnpm)
```sh
npm install pnpm -g
```

### A Great Web Environment

## Got started

### Clone this project and debug.
1.Clone and Install dependencies.
```sh
git clone https://github.com/flutas-web/ADOJAS.git
cd ADOJAS
pnpm install
```

2.Debug
```sh
pnpm tauri android init
### ↑Init ↓Debug
pnpm tauri android dev
```

### Build Release Version
```
$ pnpm tauri android build
```



