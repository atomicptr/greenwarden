# Greenwarden

A fork of the Bitwarden browser extension, which only serves the purpose so that I can install two seperate versions of it.
Because this is currently the only way to use two Bitwarden servers at the same time.

This will be abandonned as soon as Bitwarden implements the "Client Profiles" feature.

## Why Green?

To differentiate my work and my private Bitwarden extensions I had to change its color. I went with green because my companies CI is green as well.

## How to use

First you need to build the project like this:

```bash
$ git clone git@github.com:atomicptr/greenwarden.git
$ cd greenwarden
$ npm install
$ npm run build
```

Then you have to go to your Browser and install an extension from a directory which in this case will be the build directory.

# Bitwarden Browser Extension

<a href="https://chrome.google.com/webstore/detail/bitwarden-free-password-m/nngceckbapebfimnlniiiahkandclblb" target="_blank"><img src="https://imgur.com/3C4iKO0.png" width="64" height="64"></a>
<a href="https://addons.mozilla.org/firefox/addon/bitwarden-password-manager/" target="_blank"><img src="https://imgur.com/ihXsdDO.png" width="64" height="64"></a>
<a href="https://www.microsoft.com/store/p/bitwarden-free-password-manager/9p6kxl0svnnl" target="_blank"><img src="https://imgur.com/vMcaXaw.png" width="64" height="64"></a>
<a href="https://addons.opera.com/extensions/details/bitwarden-free-password-manager/" target="_blank"><img src="https://imgur.com/nSJ9htU.png" width="64" height="64"></a>
<a href="https://bitwarden.com/download/" target="_blank"><img src="https://imgur.com/ENbaWUu.png" width="64" height="64"></a>
<a href="https://chrome.google.com/webstore/detail/bitwarden-free-password-m/nngceckbapebfimnlniiiahkandclblb" target="_blank"><img src="https://imgur.com/EuDp4vP.png" width="64" height="64"></a>
<a href="https://chrome.google.com/webstore/detail/bitwarden-free-password-m/nngceckbapebfimnlniiiahkandclblb" target="_blank"><img src="https://imgur.com/z8yjLZ2.png" width="64" height="64"></a>
<a href="https://addons.mozilla.org/firefox/addon/bitwarden-password-manager/" target="_blank"><img src="https://imgur.com/MQYBSrD.png" width="64" height="64"></a>

The Bitwarden browser extension is written using the Web Extension API and Angular.

![](https://raw.githubusercontent.com/bitwarden/brand/master/screenshots/browser-chrome.png "My Vault")

# Build/Run

**Requirements**

- [Node.js](https://nodejs.org) v8.11 or greater
- [Gulp](https://gulpjs.com/) (`npm install --global gulp-cli`)
- Chrome (preferred), Opera, or Firefox browser

**Run the app**

```
npm install
npm run build:watch
```

You can now load the extension into your browser through the browser's extension tools page:

- Chrome/Opera:
  1. Type `chrome://extensions` in your address bar to bring up the extensions page.
  2. Enable developer mode (checkbox)
  3. Click the "Load unpacked extension" button, navigate to the `build` folder of your local extension instance, and click "Ok".
- Firefox
  1. Type `about:debugging` in your address bar to bring up the add-ons page.
  2. Click the `Load Temporary Add-on` button, navigate to the `build/manifest.json` file, and "Open".

# Contribute

Code contributions are welcome! Please commit any pull requests against the `master` branch. Learn more about how to contribute by reading the [`CONTRIBUTING.md`](CONTRIBUTING.md) file.

Security audits and feedback are welcome. Please open an issue or email us privately if the report is sensitive in nature. You can read our security policy in the [`SECURITY.md`](SECURITY.md) file.
