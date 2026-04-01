# cliprec.py

**Clipboard Monitoring Script Analysis**

This Python script uses the `pyperclip` library to continuously monitor the system clipboard for changes. It prints the new content to the console whenever it detects a change.

**Breakdown:**

1. **Importing Libraries:**
   - `import pyperclip`: Loads the `pyperclip` library, which allows the script to interact with the system clipboard.
   - `import time`: Loads the `time` library, which is used to add a delay between clipboard checks.

2. **Initial Output and Variable Initialization:**
   - `print('Recording clipboard... (Ctrl-C to stop)')`: Prints a message to the console, indicating that the script is starting to record the clipboard's contents and that it can be stopped by pressing Ctrl+C.
   - `previous_content = ''`: Initializes a variable to store the previous clipboard content. This variable is used to compare with the current clipboard content.

3. **Infinite Loop:**