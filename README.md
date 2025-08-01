# ⌨️ Simple Keylogger (Educational Use)

A basic Python keylogger script built using the `pynput` library. It logs every keystroke to a text file—ideal for understanding how keyboard event listeners work in Python.

> ⚠️ **Note:** This project is for educational purposes only. Unauthorized use of keyloggers can violate privacy laws and ethical guidelines.

## 🚀 Features

- Records both regular and special key presses
- Logs keys with timestamps using Python's `logging` module
- Saves data to a file called `key_log.txt`
- Stops automatically when the ESC key is pressed

## 🧰 Requirements

- Python 3.x
- `pynput` module (install via `pip install pynput`)

## 💻 Usage

Run the script in a terminal:

```bash
python TASK 4.py
```

You'll see:

```bash
Keylogger started... Press ESC to stop.
```

Keystrokes will be recorded in `key_log.txt`.

## 🐞 Notes

Make sure to correct the line below to ensure the script runs:

```python
if __name__ == "_main_":
```

Change it to:

```python
if __name__ == "__main__":
```

## 📁 File Structure

- `TASK 4.py` – The Python script that logs keyboard events
- `key_log.txt` – Output file that stores the log of key presses

## 📄 License

This code is intended purely for academic demonstration. Do not use it for malicious purposes or to monitor systems without permission.

---

Want help writing a disclaimer or README badge? Happy to help make it even more professional!
