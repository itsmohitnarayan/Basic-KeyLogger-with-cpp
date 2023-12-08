# Keylogger Program

This C++ program is a simple keylogger that logs keystrokes and writes them to a file named "log.txt". The keylogger runs in the background and hides the console window to avoid detection. It utilizes the Windows API for keyboard input monitoring.

## Features

- Logs keystrokes and writes them to a text file.
- Special keys such as Enter, Shift, Control, Caps Lock, Tab, and Alt are logged as well.
- Runs in the background, minimizing the visibility of the console window.
- Utilizes the Windows API for keyboard input monitoring.

## Usage

1. **Compilation:**
   - Compile the program using a C++ compiler. For example:
     ```bash
     g++ keylogger.cpp -o keylogger
     ```

2. **Execution:**
   - Run the compiled executable:
     ```bash
     ./keylogger
     ```

3. **Logging:**
   - The program will start logging keystrokes in the background.
   - The logged data will be stored in a file named "log.txt" in the same directory as the executable.

## Important Note

This keylogger program is intended for educational purposes only. Unauthorized use of keyloggers is illegal and unethical. Use this program responsibly and only on systems where you have explicit permission to monitor keystrokes.

## Disclaimer

The author of this code and the associated readme file is not responsible for any misuse or damage caused by the keylogger. This code is provided as-is for educational purposes, and users are expected to comply with legal and ethical standards.
