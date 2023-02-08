# Chrome Extension Boilerplate with TypeScript, SCSS and Webpack

This project is a boilerplate for building Chrome extensions using TypeScript, SCSS, and Webpack. It provides a solid and simple starting point for building robust and maintainable extensions.

## Features
- TypeScript for static typing and improved code quality
- SCSS for styling
- Webpack for bundling and optimization

## Quick Start
To get started, clone the repository and install the dependencies:

```bash
git clone https://github.com/SamuPert/chrome-extension-boilerplate.git
cd chrome-extension-boilerplate
npm install
```

Next, build the extension using webpack:

```bash
npm run build
```

Finally, load the extension into Chrome:

Open Chrome and navigate to `chrome://extensions/`.
- Enable "Developer mode".
- Click "Load unpacked".
- Select the `dist` folder from the cloned repository.
- The extension should now be loaded and running in your browser.

## Development
To start a development server with hot reloading, run the following command:

```bash
npm run dev
```

This will automatically compile the extension whenever changes are made to the code.

## Deployment
To build the extension for production, run the following command:

```bash
npm run build
```

The optimized and bundled extension will be placed in the dist folder, ready for deployment.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.