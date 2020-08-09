# Create Vue/TSX Component Folder

Quickly create folder with .tsx and .scss files.
Based on [Create Vue/TypeScript Component Folder](https://github.com/ohanqo/create-vuets-component-folder) plugin.

Demo: ![Demo](https://media.giphy.com/media/THyeNZMf4DK6zO8Abb/giphy.gif)

## Usage

Command palette: "Create Vue/TSX Component Folder"

## Configuration Example

```
"createVueTsxComponentFolder.createSCSSFile": true,
"createVueTsxComponentFolder.exclude": {
  "node_modules": true,
  "node_modules_electron": true,
  "dev": true,
  "dist": true
},
"createVueTsxComponentFolder.showInformationMessages": true,
"createVueTsxComponentFolder.convenienceOptions": ["current", "last", "root"]
```

## Contributing

1. Clone the repo
2. `yarn install`
3. Add your feature or fix (in `src/`) with test coverage (in `test/`)
4. Launch the extension and do some manual QA (via Debug > Launch Extension)
5. Run the tests (via Debug > Launch Tests)
6. Run the linter: `yarn run lint`
7. Open a PR
