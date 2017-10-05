# Installation

To watch this email, your computer needs [Node.js](https://nodejs.org/en/) 7.x. I prefere 7.10.1. If you have later version, you need to install [NVM](https://github.com/creationix/nvm) if you use normal OS, if you use Windows, like and i do, you need [NVM-Windows](https://github.com/coreybutler/nvm-windows)

## Then use commands

```bash
nvm install 7.10.1
nvm use 7.10.1
nvm list
node -v
```

nvm list how you something like this:
```
  8.6.0t
* 7.10.1 (Currently using 64-bit executable)
  6.11.3
```

## Build Commands

Run `npm start` to kick off the build process. A new browser tab will open with a server pointing to your project files.

Run `npm run build` to inline your CSS into your HTML along with the rest of the build process.