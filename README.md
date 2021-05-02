# Vikrant Maniar Take home test


## Installation

Intsall [Homebrew](https://brew.sh/)

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Under `takehome` folder

```bash
brew install node
npm install
```

## Run test

```
npm run test         # headless, on Electron
npm run headedTest   # headed, on Electron
npm run chromeTest   # headed, on Chrome
```

## Test Report
All tests generate [mochawesome](https://www.npmjs.com/package/mochawesome-report-generator) report under `mochawesome-report` folder
