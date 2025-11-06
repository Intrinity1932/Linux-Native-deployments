# yt-dlp Downloader GUI (Tkinter)

A clean, dark-themed, fully standalone GUI wrapper for **yt-dlp**, built using **Tkinter**. Just run the Python file and you get a professional desktop app for downloading audio and video.

---

## ✅ Features

* Slick dark UI using pure Tkinter
* MP3 download with selectable quality
* Thumbnail embedding for audio
* Video download up to 4K
* Subtitle embedding
* Real-time terminal output inside the GUI
* Automatic path selection
* Get video info (title + duration)
* Threaded downloads
* Uses only: **Tkinter + yt-dlp**

---

## 📦 Requirements

Only TWO requirements:

### **1. yt-dlp** (must be installed)

```sh
pip install yt-dlp
```

### **2. Tkinter**

Usually comes preinstalled with Python. If not:

* **Linux (Debian/Ubuntu):**

  ```sh
  sudo apt install python3-tk
  ```
* **Arch:**

  ```sh
  sudo pacman -S tk
  ```
* **Windows:** included
* **Mac:** included

### ✅ FFmpeg (Recommended)

For MP3 conversion and merging formats.

Linux:

```sh
sudo apt install ffmpeg
```

Windows: Download from [https://ffmpeg.org](https://ffmpeg.org)

---

## 📁 Repository Structure

```
yt-dlp-gui/
│
├── README.md        # This file
├── requirements.txt # Optional file
└── ytdlp_gui.py     # The main GUI application
```

---

## 📄 requirements.txt

```
yt-dlp
```

Tkinter not included because OS-level.

---

## 🚀 How to Run

```sh
python ytdlp_gui.py
```

That’s it. The GUI opens instantly.

---

## 🛠️ Packaging Into .EXE (Optional)

Using PyInstaller:

```sh
pyinstaller --noconsole --onefile ytdlp_gui.py
```

Output will be inside:

```
dist/ytdlp_gui.exe
```

---

## ❤️ Notes

* No external framework
* Fully offline working
* Designed to be lightweight

If you want, I can also generate:
✅ setup.py
✅ license file
✅ gif preview for repo
✅ pip-installable package structure

Just say the word.
