1. **Install Google Chrome**:
   - Download and install [Google Chrome](https://www.google.com/chrome/) if it's not already installed.

2. **Run Command with Full Path**:
   - Use the full path to the Chrome executable in your command:
     ```bash
     "/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" --headless --print-to-pdf https://developer.chrome.com/
     ```

3. **Create an Alias (Optional)**:
   - For easier access, create an alias for Chrome by adding the following line to your `~/.zshrc` file:
     ```bash
     alias chrome="/Applications/Google Chrome.app/Contents/MacOS/Google Chrome"
     ```
   - Save the file and apply the changes:
     ```bash
     source ~/.zshrc
     ```
   - Now you can use the `chrome` command to run Chrome in headless mode:
     ```bash
     chrome --headless --print-to-pdf https://developer.chrome.com/
     ```
