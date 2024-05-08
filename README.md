# Keylogger using Tkinter and pynput

This Python script demonstrates a basic keylogger implementation using Tkinter for the graphical user interface and pynput for capturing keyboard events. It logs key presses, holds, and releases to both a text file (`key_log.txt`) and a JSON file (`key_log.json`).

## Requirements
- Python 3.x
- Tkinter
- pynput

## Installation
1. Install the required dependencies:
    ```
    pip install pynput
    ```
2. Clone or download the script.

## Usage
1. Run the script:
    ```
    python keylogger.py
    ```
2. Click on the "Start" button to begin keylogging.
3. To stop keylogging, click on the "Stop" button.

## Functionality
- Key presses, holds, and releases are captured.
- Key events are logged to both a text file (`key_log.txt`) and a JSON file (`key_log.json`).
- The "Start" button initiates the keylogger, while the "Stop" button halts it.

## Files
- `keylogger.py`: The main Python script.
- `key_log.txt`: Text file containing the logged keys.
- `key_log.json`: JSON file containing the logged keys in structured format.
