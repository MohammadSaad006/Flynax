# 🚀 Flynax v0.1.0-alpha Release Notes

Welcome to the first official alpha release of **Flynax**!

Flynax is a "Release Candidate" for developers who want to experiment with a high-performance, Python-syntax language that compiles directly via LLVM.

## ✨ New in this Release

- **LLVM Backend**: Full integration with LLVM for native performance.
- **Interactive I/O**: Added `input()` and `string_to_int()` for building interactive apps.
- **WebAssembly Target**: Build for the browser with `-target=wasm`.
- **Package Manager**: Integrated `flpm` with cloud registry support.
- **Standard Library**:
    - **UI**: Native SDL2 graphics and animations.
    - **DB**: Built-in SQLite support.
    - **Web**: HTML parsing and networking via Winsock.
- **VS Code Support**: Official extension with syntax highlighting.

## 🛠️ Improvements
- Automatic standard library linking on Windows.
- Optimized IR generation for `main()` entry points.
- Improved error diagnostic snippets with line/column tracking.

## ⚠️ Known Limitations
- Garbage collection is still experimental (manual memory management recommended for complex apps).
- Error messages on WASM targets can be cryptic (source mapping in progress).

## 📥 Get Started
Download the binary zip below or use the one-liner installer:
```powershell
powershell -Command "iwr -useb https://raw.githubusercontent.com/flynax-lang/flynex/main/setup.ps1 | iex"
```
