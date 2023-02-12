# Vue Devtools for Safari

This is a port of the vue-devtools extension available for Google Chrome and Mozilla Firefox browsers.
This repository contains an Xcode project that ports the extension using an existing Chrome extension installation into a Swift-based Safari Extension.

## How to run this project

To install Vue-devtools in Safari, follow these steps:

### 1. Install Xcode
If not already installed, you need to install Xcode to run the project as well as build the Safari Extension.
<br>There are multiple ways to download the latest version of Xcode:-
- via the Mac App Store.
- via tha Apple Developers website.

Make sure you have more than 40-45 GBs free on your disk to ensure smooth installation of the IDE.

### 2. Enable Developer mode in Safari to allow Unsigned Extensions.
1. To enable Developer mode in Safari, Press ⌘, to open the Safari App Preferences.
2. Navigate to the 'Advanced' Tab
3. Check the 'Show Develop menu in menu bar'. You should now be able to see the 'Develop' tab appear after the 'Bookmarks' tab in the menu bar.
4. Open the 'Develop' menu and click the 'Allow Unsigned Extensions' option in the menu.
5. Close Safari to make sure the changes take effect.

### 3. Clone this repository.
1. Open Terminal or your preferred Terminal emulator.
2. Navigate to the directory you want to save this codebase in.
3. Clone the repository using the command: `git clone https://github.com/arizsiddiqui/vue-devtools-for-safari`
4. This codebase should now be available on your local machine.

### 4. Run the project.
1. In Finder navigate inside this repository until you find the 'Vue.js devtools.xcodeproj' file.
2. Double click this file to open the entire project in Xcode.

### 5. Bundle the source code into a Safari WebExtension App.
1. In Xcode, open the 'Product' menu in the menu bar and click 'Archive'. Xcode will start building the project to be bundled into an application.
2. In the Archives window that then appears, choose 'Distribute App', and 'Copy App' in the distribution dialog box.
3. Choose the destination folder for the bundled application.

### 6. Add the extension to Safari.
1. In Finder, navigate to the destination folder. Here you should find an application by the name of 'Vue.js devtools.app'.
2. Run the app by double clicking on it.
3. Click the button inside to open Safari Extensions.
4. Check the box next to the devtools extension to enable it in Safari.