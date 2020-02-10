# ElectronJS notes

- webcontents.loadFile doesn't use relative paths from the location of the main.js file, but from the package.json file.
- In order to debug things in the browser, use the inspector.
- nodeIntegration changed from true to false in version 5. Electron is currently at version 8.
- When something breaks which should, check that the package uses semver.
