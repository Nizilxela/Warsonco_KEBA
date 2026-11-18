# KEBA KAIRO Syntax

VS Code syntax highlighting for KEBA KeMotion3 KAIRO source files:

- `.tip` — program code
- `.tid` — static variable declarations and data types

## Install from folder

1. Extract this folder to a permanent location.
2. In VS Code open **Extensions** (`Ctrl+Shift+X`).
3. Open the `...` menu and select **Install from VSIX...** only if you have a VSIX package. For folder-based development, use **File → Open Folder...** to open this extension folder, then press `F5` to launch an Extension Development Host.
4. To install it as a normal extension without VSIX packaging, copy the folder `keba-kairo-syntax` into your VS Code extensions directory and restart VS Code.

## Notes

- KAIRO is case-sensitive; command patterns preserve documented spelling.
- The grammar highlights documented built-ins and common language constructs. User-defined routines and variables remain ordinary identifiers.
- `//` is a line comment. `##` disables a complete instruction line and is highlighted separately in `.tip` files.
- This is syntax highlighting, not a compiler or semantic validator.
