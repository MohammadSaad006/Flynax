# 🤝 Contributing to Flynax

We are thrilled that you want to contribute to Flynax! As a new programming language, there are many ways to help:

## 🛣️ Where to Start?

1.  **Bug Reports**: If you find a crash or a syntax that doesn't parse correctly, please open an issue!
2.  **Language Features**: Check the Roadmap in the [README](./README.md) for planned features.
3.  **Standard Library**: We need more built-in functions for math, strings, and OS interaction.
4.  **Documentation**: Improve the guides or add more examples to the `examples/` folder.

## 🛠️ Development Environment

### Prerequisites
- LLVM 17+ (with Clang)
- CMake 3.10+
- A C++17 compliant compiler (MSVC, GCC, or Clang)

### Building the Compiler
```bash
mkdir build
cd build
cmake ..
cmake --build .
```

## 📜 Coding Style

- **Compiler**: Modern C++17. Use descriptive names and keep the Visitor pattern clean in `codegen.cpp`.
- **Runtime**: ANSI C for maximum compatibility.
- **Library**: Flynax syntax (`.fx` files).

## 🚀 Pull Request Process

1.  Fork the repository.
2.  Create a feature branch.
3.  Ensure your change includes a test in the `examples/` folder.
4.  Submit a PR with a clear description of the change.

Thank you for helping us build the next generation of systems programming!
