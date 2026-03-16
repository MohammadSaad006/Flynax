# 📥 Installing Flynax

Flynax can be installed quickly via our cloud script or manually from our release binaries.

## 🌐 1. Cloud Installation (Recommended)

Open **PowerShell** and run the following "one-liner":

```powershell
powershell -Command "iwr -useb https://raw.githubusercontent.com/flynax-lang/flynex/main/setup.ps1 | iex"
```

### What this does:
1. Downloads the latest Flynax binaries.
2. Extracts them to `$HOME\.flynax`.
3. Automatically adds Flynax to your **User PATH**.

---

## 📦 2. Manual Installation

1. Download the latest `flynax-v0.1.0-win64.zip` from the [Releases](https://github.com/flynax-lang/flynex/releases) page.
2. Extract the contents to a folder (e.g., `C:\flynax`).
3. Add the `bin` folder to your System Environment Variables (PATH).

---

## 🛠️ 3. Backend Prerequisites

Flynax requires **LLVM/Clang** to be installed on your system to link the final binaries.

### Windows (winget):
```powershell
winget install -e --id LLVM.LLVM
```

### Linux:
```bash
sudo apt install clang  # Ubuntu/Debian
```

---

## ✅ Verification

Restart your terminal and run:
```bash
flynax --version
```

If you see `Flynax Compiler v0.1.0`, you are ready to build!
