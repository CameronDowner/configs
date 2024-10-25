# Opinionated Guide to Setting Up a Mac

This is the software and configuration I add to a new Mac. I'm a Java / Node developer, so this guide is tailored to
that.

## Chrome

I prefer to use Chrome as my browser.

[Download Chrome](https://www.google.com/chrome/)

### Chrome Extensions

- JSON Viewer
    - This will make JSON responses prettier in the browser.
    - [Download JSON Viewer](https://chrome.google.com/webstore/detail/json-viewer/gbmdgpbipfallnflgajpaliibnhdgobh)
- Cookie Editor
    - I don't typically use this for editing cookies, but it's a more convenient way to view cookies.
    - [Download Cookie Editor](https://chromewebstore.google.com/detail/cookie-editor/iphcomljdfghbkdcfndaijbokpgddeno)
- React Developer Tools
    - [Download React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi)
- Loom
    - I use Loom to share videos and demonstrate new features
    - [Download Loom](https://chrome.google.com/webstore/detail/loom-for-chrome/liecbddmkiiihnedobmlmillhodjkdmb)
- Testing Playground
    - This is a tool I use to test discover the best testing library queries for a given element.
    - [Download Testing Playground](https://chrome.google.com/webstore/detail/testing-playground/hejbmebodbijjdhflfknehhcgaklhano)
- uBlock Origin
    - I use this to block ads and trackers.
    - [Download uBlock Origin](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm)

## iTerm2

I prefer to use iTerm2 as my terminal.

[Download iTerm2](https://www.iterm2.com/)

## Homebrew

Homebrew is a package manager for macOS.

[Install Homebrew](https://brew.sh/)

## MacOS Command Line Tools

These are a requirement for other tools and development in general, and they also provide helpful commands, such
as git, that aren't included by default. I prefer to install them early on.

```bash
xcode-select --install
```

## JetBrains Toolbox

[Download JetBrains Toolbox](https://www.jetbrains.com/toolbox-app/)

I use JetBrains Toolbox to manage my installations and updates of any JetBrain products. It's much easier as it allows
me to automatically install everything I need, keep it up-to-date, and have shortcuts to any projects I use with a
JetBrains IDE.

## Slack

Majority of the companies I work with use Slack for communication.

[Download Slack](https://slack.com/downloads/mac)

## Rectangle

Rectangle is a window manager that allows you to easily resize and move windows.

[Download Rectangle](https://rectangleapp.com/)

## SDKMan

I use this for managing my JDK and Maven installations.

[Download SDKMan](https://sdkman.io/install)

## NVM

I use this to install and manage my node installations. We also use it within repose to make sure we're all using the
same version of node.

I also make it so it will automatically change the Node version if it sees a `.nvmrc`
file: https://github.com/nvm-sh/nvm#calling-nvm-use-automatically-in-a-directory-with-a-nvmrc-file

[Download NVM](https://github.com/nvm-sh/nvm)
