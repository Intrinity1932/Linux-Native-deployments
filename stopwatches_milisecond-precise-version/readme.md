# High-Precision Stopwatch (Tkinter)

This project is a Tkinter-based **high-precision stopwatch** that uses the system clock (`time.time()`) to track accurate elapsed time.

Unlike the loop-condition stopwatch, this version **does use real system time**, which gives you:
- millisecond-level accuracy  
- reliable timing even if the UI lags  
- no drift over long sessions  

---

## Features
- Start, Stop, Reset controls  
- Tracks hours, minutes, seconds, and centiseconds  
- Uses `time.time()` for true elapsed-time calculation  
- Updates every 10 ms  
- Clean Tkinter interface

---

## How It Works
- `start_time` stores the moment when the stopwatch begins running.  
- On each update, the program calculates.
