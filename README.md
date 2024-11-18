(Optional)

If you'd like to make this file double-clickable (so you don't need to run it from the command line), you can create an executable file from the Python script.

#### Using `PyInstaller` to Create an Executable

1. Install `PyInstaller` if you don't have it already:
   ```bash
   pip install pyinstaller
   ```

2. Navigate to the directory where your `open_browser.py` file is located, then run the following command to create an executable:
   ```bash
   pyinstaller --onefile open_browser.py
   ```

3. After `PyInstaller` completes, you will find a standalone executable file in the `dist` folder.

   - On Windows, this will be `open_browser.exe`.
   - On macOS/Linux, it will just be `open_browser` (no extension).

4. You can now double-click this executable to automatically open your web browser and navigate to the specified URL.

---

### Alternative: Create a Windows Batch File

If you don't want to deal with Python and prefer a simple batch file approach (for Windows), you can create a `.bat` file that opens the URL directly. Here's how:

1. Open a text editor (like Notepad).
2. Write the following command:

```batch
start https://www.challengermode.com?s?Strangeways
```

3. Save the file with a `.bat` extension, e.g., `open_browser.bat`.
4. Double-click the `.bat` file to open the browser and navigate to the URL.

---

Both methods will achieve your goal
