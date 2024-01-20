**# Keylogger with FTP Upload**

**This Python script captures keystrokes and uploads the logs to an FTP server.**

**## Features:**

- Logs all pressed keys, including special keys.
- Logs keystrokes with timestamps.
- Uploads logs to a specified FTP server.
- Stops logging when the Escape key is pressed.

**## Usage:**

1. Install required libraries:
   ```bash
   pip install pynput ftplib
   ```
2. Edit the following variables in the script:
   - `logdir`: The directory to store the log file (default is the current directory).
   - FTP server details:
     - `"192.168.e.e"`: Replace with the actual FTP server IP address.
     - `"username"` and `"password"`: Replace with the FTP server credentials.
3. Run the script:
   ```bash
   python keylogger_ftp.py
   ```

**## Notes:**

- The script requires Python 3.
- Use with caution as it captures sensitive keystrokes.
- Consider security measures for the FTP server and log file storage.

**## Contributing:**

- Fork the repository.
- Make changes.
- Submit a pull request.

**## License:**

- Choose a license: [https://choosealicense.com/](https://choosealicense.com/) and add it to the repository.
