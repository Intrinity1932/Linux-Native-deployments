
---

## 🧊 AppImage Release (Portable Linux Build)

This project also includes a **fully portable AppImage build**, allowing you to run the calculator on almost any Linux distribution **without installing Python or dependencies**.

### 📦 **Build Details**

* **Format:** AppImage
* **Built on:** Ubuntu 20.04 LTS
* **Python Version:** Python 3.10.x
* **Architecture:** x86_64 (64-bit)
* **Dependencies:** None (self-contained)
* **Toolkit:** Tkinter (bundled inside)

### 🔥 **Why AppImage?**

AppImage provides:

* Zero installation – no pip, no venv
* Fully sandboxed execution
* One file → double-click → run
* Works across multiple distros:

  * Ubuntu
  * Pop!_OS
  * Debian
  * Linux Mint
  * Fedora (with FUSE)
  * Arch / Manjaro
    *(as long as FUSE or AppImageLauncher is available)*

### ▶️ **How to Run**

Download the `.AppImage` file from the releases page, then:

```bash
chmod +x AdvancedCalci-x86_64.AppImage
./AdvancedCalci-x86_64.AppImage
```

### 🛡 Notes

* AppImages created on older distros (like Ubuntu 20.04) ensure maximum forward compatibility.
* All Python runtime components, Tkinter, and UI assets are packaged inside.
* No system modifications are made.
* Does not require sudo.

