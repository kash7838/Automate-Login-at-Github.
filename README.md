# GitHub Login Automation with Python + Selenium

## 📌 Overview
This project demonstrates how to automate the GitHub login process using **Python**, **Selenium**, and **time** modules.  
The function `git_login` opens Chrome, navigates to the GitHub login page, fills in the username and password fields, and submits the form automatically.

---

## ⚙️ Features
- Launches Chrome browser via Selenium WebDriver  
- Navigates directly to GitHub login page  
- Inputs username and password  
- Clicks **Sign In** button  
- Option to keep browser session open (comment out `driver.quit()`)

---

## 🛠️ Dependencies
- Python 3.x  
- [Selenium](https://pypi.org/project/selenium/)  
- Chrome WebDriver (compatible with your Chrome version)  
- time (built-in Python module)

---

## 🚀 Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/git_login.git
