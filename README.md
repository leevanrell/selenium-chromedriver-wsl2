# Run Selenium and Chrome on WSL2 Ubuntu using Python
You can utilize this script to facilitate the installation of Chrome, Chromedriver, and Selenium on Ubuntu within the Windows Subsystem for Linux (WSL2).

# Using the repository

Clone the repository

```
git clone https://github.com/leevanrell/selenium-chromedriver-wsl2.git selenium && cd selenium
```
Update system packages

```
sudo apt update && sudo apt upgrade -y
```

Install Python-venv

```
sudo apt install python3-venv
```

Create and activate a virtual environment

```
python3 -m venv .venv && /
source .venv/bin/activate
```
Install selenium

```
pip install selenium
```

Install jq for Ubuntu/Debian OS
```
sudo apt install jq
```

Install Chrome & Chromedriver


```
chmod +x ws12_selenium_setup.sh
./ws12_selenium_setup.sh
```

Run a Python program

```
python3 selenium_chromedriver_demo.py
```
