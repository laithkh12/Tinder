# ❤️ Tinder Auto-Liker Bot

<img src="https://upload.wikimedia.org/wikipedia/commons/8/82/Tinder_logo_with_flame.png" alt="tinder-logo" width="150"/>

A Python-based automation script using **Selenium WebDriver** to automate the liking process on Tinder. This tool helps you swipe right effortlessly within Tinder's free daily limit.

---

## 📋 Features

- Automates login via Facebook credentials.
- Handles pop-ups for location and notification permissions.
- Skips and resumes when encountering "It's a Match!" pop-ups.
- Swipes right 100 times (configurable).

---

## ⚙️ Prerequisites

Before you start, ensure you have the following:

1. **Python 3.7+**
2. **Google Chrome Browser**
3. **ChromeDriver** compatible with your Chrome version.
4. Install required Python libraries:
   ```bash
   pip install selenium
    ```
---
## 🚀 How to Use
1. Clone this repository or copy the script into your working directory.
2. Update the **FB_EMAIL** and **FB_PASSWORD** variables with your Facebook login credentials.
3. Run the script
---
## 📂 Script Workflow
1. Open Tinder
  - Launches Tinder in a Chrome browser.
2. Facebook Login
  - Logs in using your Facebook credentials by handling the pop-up window.
3. Set Permissions
  - Automatically accepts location and notification permissions.
4. Auto-Swiping
  - Swipes right up to 100 times (or more if configured) and gracefully handles pop-ups for matches or delays.
---
## 🖋️ Example Configuration
Update these variables in the script:
```python
FB_EMAIL = "your_email@example.com"
FB_PASSWORD = "your_password"
```
---
## ⚠️ Important Notes
- CAPTCHA or Account Lockouts: Tinder or Facebook may flag automated behavior. Use responsibly and avoid excessive use.
- CAPTCHA or Account Lockouts: Tinder or Facebook may flag automated behavior. Use responsibly and avoid excessive use.
```python
for n in range(100):
```
- Ensure the script is up-to-date with Tinder's latest web structure.
---
## 🛠 Troubleshooting
- **Browser Not Opening**? Ensure the chromedriver executable is installed and added to your system's PATH.
- **Login Errors**? Verify your Facebook credentials and check for changes in Tinder's login flow.
- **Element Not Found Errors**? Confirm that the XPATHs in the script match the current Tinder web layout.
---
## 🤝 Contributing
Contributions are welcome! Feel free to submit a pull request or suggest improvements.
---
## 📄 License
This project is licensed under the MIT License. See the LICENSE file for details.
---
## 🌟 Acknowledgments
- Powered by Selenium WebDriver.
- Inspired by the need to automate repetitive tasks.
---
