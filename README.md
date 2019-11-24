# Advanced New Component

Quickly create folder with .ts, .vue and .scss files.
Based on AdvancedNewFile plugin.

![Demo](https://media.giphy.com/media/dXuMQhjg9NYoAPVhFe/giphy.gif)

## Usage

Command palette: "Advanced New Component"

## Configuration Example

```
"createVueTsComponentFolder.createSCSSFile": true,
"createVueTsComponentFolder.exclude": {
  "node_modules": true,
  "node_modules_electron": true,
  "dev": true,
  "dist": true
},
"createVueTsComponentFolder.showInformationMessages": true,
"createVueTsComponentFolder.convenienceOptions": ["current", "last", "root"]
```

## Contributing

1. Clone the repo
2. `yarn install`
3. Add your feature or fix (in `src/`) with test coverage (in `test/`)
4. Launch the extension and do some manual QA (via Debug > Launch Extension)
5. Run the tests (via Debug > Launch Tests)
6. Run the linter: `yarn run lint`
7. Open a PR
