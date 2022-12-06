# Flutter QR code generator - Chrome extension

Chrome extension created using Flutter for generating QR code from either a text or URL. The QR code's background and foreground colors are also customizable.

## Usage
To use this project as a Chrome extension, follow the steps below:

1. Clone the repo

2. From the project directory, run:
```sh
flutter build web --web-renderer html --csp
```
3. Go to the following URL from Chrome browser:
```sh
chrome://extensions
```
4. Enable the Developer mode.

5. Click Load unpacked. Select the `<project_dir>/build/web` folder.

This will install the extension to your Chrome browser and then you will be able to access the extension by clicking on the extension icon.