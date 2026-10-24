# @x12i/mdreports-core usage example

Markdown Reports Studio rendering engine: HTML, PDF, DOCX, and PPTX export plus template store.

This consuming application demonstrates **render local markdown with a bundled report template** using the published npm package, pinned to `0.4.0`.

## Run

Requires Node.js 24 or newer and npm. The example needs no service credentials.

```sh
npm install --ignore-scripts
npm start
```

## Example

[`src/index.mjs`](src/index.mjs) contains the complete example. Assertions check the demonstrated behavior and the program prints a small result.

## When to use the package

- Embed Markdown report rendering in a Node application.
- Use a selected template for HTML or supported document exports.

## Links

- [npm package](https://www.npmjs.com/package/@x12i/mdreports-core)

The `package.json` in this repository is private to prevent accidental publication of the example application under an npm package name.

## Validation scope

This example consumes bundled assets or deterministic local fixtures. It does not contact providers, acquire real records, seed a database, or persist a production graph. Report examples check HTML generation only. Theme examples generate `preview.html`; visual appearance still needs browser review.
