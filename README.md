# ![nitter-redirect](images/icon32.png) Nitter Redirect

Fork with support X.com

A simple browser extension that redirects Twitter requests to [Nitter](https://github.com/zedeus/nitter) instead.

No unnecessary permissions required, only listens for and redirects requests made to `twitter.com`, `x.com`, `www.twitter.com`, `mobile.twitter.com`, `pbs.twimg.com` & `video.twimg.com`, nothing else.

Allows for setting custom [Nitter instances](https://github.com/zedeus/nitter/wiki/Instances) and toggling redirects on & off.

## Download for Brave or Chrome

  [1]: https://cloud.githubusercontent.com/assets/24923693/21724562/26754b04-d435-11e6-9654-779c17c2ebcf.png
  [2]: https://github.com/Philippe734/nitter-redirect-for-x/releases
ZIP file : [![Linux][1]][2]

## Build on Linux

```
sudo apt update
sudo apt install nodejs npm git -y
sudo npm install --global web-ext
git clone https://github.com/Philippe734/nitter-redirect-for-x.git
cd nitter-redirect-for-x
web-ext build
```

Extension will be in: /home/YourName/nitter-redirect-for-x/web-ext-artifacts/nitter-redirect-1.1.6.zip

## Installation on Brave or Chrome
- Extract the .zip file into a permanent folder, because browser use always the folder for load the extension
- Open Brave and go to:
  - chrome://extensions/
- Enable Developer Mode (top right corner).
- Click on "Load unpacked".
- Select the folder where you extracted the extension.
