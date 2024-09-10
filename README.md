# PRODIGY_CS_04 SilentStroke

# Keylogger using `pynput` 📝

This is a simple keylogger script implemented in Python using the `pynput` library. The script captures the keys pressed on the keyboard and logs them into a file named `keyfile.txt`. It's a basic demonstration of how to handle keyboard input in Python and log the keystrokes for later use.

## How It Works ⚙️

- The script listens for key presses using the `pynput.keyboard.Listener` class.
- Whenever a key is pressed, the `keyPressed` function is triggered, logging the key to `keyfile.txt`.
- The keys are appended to the file as they are pressed.
- It handles errors when special keys (like Shift, Ctrl, etc.) are pressed by using exception handling.


### Key Features ✨

- **Real-time key logging**: Logs every key pressed in real-time to a file.
- **Error handling**: Gracefully handles special keys by catching exceptions.
- **Simple and lightweight**: Uses the `pynput` library, which is easy to install and use.

## Requirements 📦

- `pynput` library

You can install the required library using pip:

```bash
pip install pynput
```

## How to Run 🚀

1. **Download** the repository.
```bash
  https://github.com/ThwariqAnwar/PRODIGY_CS_04.git
   ```
2. **Install the required dependencies** using the command above.
3. Run the script:

```bash
python keylogger.py
```

4. The script will start logging key presses. Check `keyfile.txt` to see the logged keys.

## Ethical Considerations:
- Always obtain explicit consent from users before running such a program.
- Avoid using or distributing keyloggers without appropriate permissions, as it can violate privacy and legal regulations.
