# My UI Library Monorepo 🚀

This monorepo contains a simple UI library with a counter component using Snabbdom.

## Project Structure 📂

The project follows a monorepo structure using Lerna:

```plaintext
my-ui-library-monorepo/
  ├── packages/
  │   ├── ui-components/
  │   │   ├── src/
  │   │   │   ├── Counter.js
  │   │   │   └── App.js
  │   │   ├── package.json
  │   │   └── rollup.config.js
  │   └── ui-utils/
  │       ├── src/
  │       │   └── ... (other utility files)
  │       ├── package.json
  │       └── rollup.config.js
  ├── lerna.json
  ├── package.json
  ├── index.html
  └── app.js
```


## Troubleshooting 🛠️

If the webpage is not showing anything, check the following:
- Open the browser's console for error messages.
- Verify file paths and imports in app.js and Counter.js.
- Ensure Snabbdom functions are imported correctly.

Feel free to customize the project and use it as a starting point for your UI library! 🎉

```

