# Calameo-SVG-Downloader

This source code is a SVG downloader for all books on `https://global.oup.com/education/support-learning-anywhere/key-resources-online/?region=uk`

it will support to all Calameo website.

### Required Dependencies

1. Python 3.6+
2. Selenium
3. Selenium Chrome WebDriver
4. Requests

### How to install (Ubuntu 18.04)

1. Install prerequisites
```
sudo apt update
sudo apt install python3-venv xorg gtk2-engines-pixbuf dbus-x11 xfonts-base xfonts-100dpi xfonts-75dpi xfonts-cyrillic xfonts-scalable imagemagick x11-apps unzip xvfb libxi6 libgconf-2-4 default-jdk
```
2. Install Google Chrome
```
sudo curl -sS -o - https://dl-ssl.google.com/linux/linux_signing_key.pub | sudo pt-key add
echo "deb [arch=amd64]  http://dl.google.com/linux/chrome/deb/ stable main" | sudo tee /etc/apt/sources.list.d/google-chrome.list
sudo apt update
sudo apt install google-chrome-stable
```
3. Clone repo
```
git clone https://github.com/atlonxp/Calameo-SVG-Downloader.git
cd Calameo-SVG-Downloader/
python3 -m venv calameo
source calameo/bin/activate
pip3 install selenium
pip3 install requests
```
4. Install ChromeDriver
```
mkdir -p ./data/drivers
cd ./data/drivers
wget https://chromedriver.storage.googleapis.com/85.0.4183.87/chromedriver_linux64.zip
unzip chromedriver_linux64.zip
```
Feel free to you.
Enjoy! 

**atlonxp**
