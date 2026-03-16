# ⚡ Flynax: The Beast Language for the Modern Era

**Flynax** is a high-performance, compiled programming language designed to combine the **clean syntax of Python** with the **raw power of C++**. Powered by LLVM, Flynax compiles to native machine code that beats Python in raw benchmarks.

![Flynax Logo](https://raw.githubusercontent.com/flynax-lang/flynex/main/assets/logo.png)

## 🚀 Key Features

- **⚡ Blazing Fast**: Native compilation via LLVM (Modular Real IR mode).
- **🐍 Pythonic Syntax**: Clean, indentation-based logic. No `def` or `self` boilerplate.
- **🛠️ Professional Ecosystem**: Integrated package manager (`flpm`) and cloud registry.
- **🌐 Universal**: Compiles to Native (Windows/Linux) and WebAssembly (WASM).
- **🔋 Batteries Included**: Native support for SQLite, JSON, Networking, and SDL2 Graphics.

---

## 💻 Quick Installation (Windows)

Install Flynax in seconds with our professional cloud installer:

```powershell
powershell -Command "iwr -useb https://raw.githubusercontent.com/flynax-lang/flynex/main/setup.ps1 | iex"
```

*For manual installation or other platforms, see [INSTALLATION.md](./INSTALLATION.md).*

---

## 📝 Syntax at a Glance

```fx
# A simple interactive sum program
main():
    print("Welcome to Flynax!")
    string name = input("Enter your name: ")
    print("Hello, " + name)
    
    int a = 176
    string bs = input("Enter a number to add to 176: ")
    int b = string_to_int(bs)
    
    int result = a + b
    print("Beast Result: " + result)
```

---

## 🗺️ Roadmap

- [x] LLVM Native Code Generation
- [x] WebAssembly Target Support
- [x] Standard Library (Math, String, I/O)
- [x] Package Manager (`flpm`)
- [ ] Garbage Collection (In Progress)
- [ ] Standard Library "Magic" Imports

---

## 🤝 Contributing

Flynax is an open-source project. We welcome contributions to the compiler, standard library, and documentation! See [CONTRIBUTING.md](./CONTRIBUTING.md) for details.

## 📄 License

Flynax is released under the **MIT License**.
