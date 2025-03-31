# swag-labs-automation

Automated tests for [SauceDemo](https://www.saucedemo.com/) using Playwright with TypeScript. This project validates key user flows like login, product interactions, and checkout. Supports headless/headed execution and generates reports. Follow the README for setup instructions.

## System requirements

- Node.js 18+
- Windows 10+, Windows Server 2016+ or Windows Subsystem for Linux (WSL).
- MacOS 12 Monterey, MacOS 13 Ventura, or MacOS 14 Sonoma.
- Debian 11, Debian 12, Ubuntu 20.04 or Ubuntu 22.04, with x86-64 or arm64 architecture.

## Recommended Development Environment

We recommend using [Visual Studio Code](https://code.visualstudio.com/) to work with this project. Visual Studio Code provides excellent support for JavaScript and TypeScript development, including extensions that enhance the Playwright testing experience.

### Steps to Get Started with Visual Studio Code

**Clone the Project**
Open Visual Studio Code, and use the command palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on macOS) to select **Git: Clone**. Enter the repository URL to clone this project to your local machine.

### Testing execution

### Node JS and playwright

```sh
# To install project dependencies run:
npm install
```

```sh
# To execute all the tests run:
npm test
```

```sh
# To open last HTML report run:
npm run report
```
