# 🚀 DevOps Lab Experiments using  Selenium

This repository includes a set of experiments demonstrating containerization with browser automation testing using Selenium and JavaScript.


## 🧪 Selenium-Based Experiments (JavaScript)

These experiments demonstrate browser automation testing using Selenium WebDriver with JavaScript.

---
open localhost:8080 for jenkins 
### 🔬 **Experiment 13:** Basic JavaScript Program with Selenium Testing

📁 Code location:
```bash
git clone https://github.com/Adivishnu15/Selenium.git
cd Selenium/13
✅ Pre-requisites:

Install Selenium IDE Chrome extension and pin it to your toolbar.

Install Node.js and required modules:

bash
Copy
Edit
sudo apt update
sudo apt install nodejs npm -y
npm init -y
npm install selenium-webdriver
💡 Optional: Install Latest Node Version

bash
Copy
Edit
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
source ~/.bashrc
nvm list-remote
nvm install v16.14.0
🔍 Install Chrome (if not already installed):

bash
Copy
Edit
google-chrome --version  # Check if installed
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo apt install ./google-chrome-stable_current_amd64.deb -y
💻 Install ChromeDriver:

bash
Copy
Edit
sudo apt install chromium-chromedriver -y
▶️ To Run:

bash
Copy
Edit
node filename.js
🔐 Experiment 14: Login Form Testing using Selenium
📁 Code location:

bash
Copy
Edit
git clone https://github.com/Adivishnu15/Selenium.git
cd Selenium/14
Files:

loginform.html

test_login.js

📦 Setup:

bash
Copy
Edit
sudo apt update
sudo apt install nodejs npm -y
npm init -y
npm install selenium-webdriver
▶️ Run the Test:

bash
Copy
Edit
node test_login.js
📄 Experiment 15: Testing results.mvsrec.edu.in using Selenium
📁 Code location:

bash
Copy
Edit
git clone https://github.com/Adivishnu15/Selenium.git
cd Selenium/15
File:

result.js

📦 Setup:

bash
Copy
Edit
sudo apt update
sudo apt install nodejs npm -y
npm init -y
npm install selenium-webdriver
▶️ Run the Test:

bash
Copy
Edit
node result.js
💡 Tips for Selenium Testing
Make sure Chrome and ChromeDriver versions are compatible.

Use await in Selenium scripts where needed for asynchronous calls.

You can open .html files locally in the browser for visual confirmation before testing.

Consider using assertions to validate test cases programmatically.

🔗 Useful Links
Selenium WebDriver Docs

Node.js Official Site

Docker Official Site

ChromeDriver Versions

📄 License
This project is licensed under the MIT License.
