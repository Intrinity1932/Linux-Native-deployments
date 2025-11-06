# Stopwatch by Pawan

This project contains a simple Tkinter-based stopwatch written in Python.

The stopwatch does **not use system real-time**.  
Instead, it uses **loop conditions with Tkinter's `after()` method**, which makes it more optimized and easier to control than relying on actual system clock syncing.

There are **two versions** included in this folder:
- **Dark version**
- **Light version**

Both versions share the same logic but differ only in UI color themes.

---

## Features
- Start, Stop, Reset functions  
- Clean Tkinter interface  
- Loop-based timing instead of actual clock time  
- Easy to modify

---

## How It Works
- A global `runner` flag controls whether the stopwatch currently runs.  
- The function `time_call()` increases seconds, minutes, and hours using simple conditions.  
- `window.after(1000, time_call)` schedules the next tick every 1 second.  
- This avoids real-time syncing and keeps the script lightweight.

---
