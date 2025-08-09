# Syntax-highlighter-for-EC72ASM

Syntax highlighter support for EC72ASM assembly in Visual Studio Code, or Code - OSS for Arch Linux.

---

## 📦 Installation

### Method 1 — From VSIX (Recommended)

**➡ [Download EC72ASM Syntax Highlighter (.vsix)](https://github.com/Gandalf2004/Syntax-highlighter-for-EC72ASM/releases/latest/download/ec72asm-syntax-0.0.1.vsix)**

1. Download the `.vsix` file from the link above or from the [Releases](https://github.com/Gandalf2004/Syntax-highlighter-for-EC72ASM/releases) page.  
2. In VS Code, open the Extensions view (`Ctrl+Shift+X`).  
3. Click the **⋯** menu in the top-right corner.  
4. Choose **Install from VSIX...** and select the downloaded file.  
5. Restart VS Code (optional but recommended).

---

### Arch Linux / Code - OSS Users

If you are using **Code - OSS** on Arch Linux, the binary might be named differently. To install via terminal:

```bash
code-oss --install-extension ec72asm-syntax-0.0.1.vsix
```
Or via the GUI:
  same as for windows asame as abouve.

## Building from Source
If you want to edit the grammar and repackage the extension yourself:
  - Install [Node.js](https://nodejs.org/en/download) and npm.
  - Clone this repository:
```bash
git clone https://github.com/Gandalf2004/Syntax-highlighter-for-EC72ASM.git
cd ec72asm-syntax/build
```
  - Package the extension:
```bash
npx vsce package
```
  This will create a `.vsix` file
  - Install it via VS Code or Code - OSS using the steps above.
