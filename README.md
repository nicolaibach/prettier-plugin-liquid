# prettier-plugin-liquid

[Prettier](https://prettier.io) plugin to make Prettier parse [Liquid](https://github.com/Shopify/liquid) files as HTML.

**This plugin doesn't provide any special formatting for the Liquid markup language!**

## Why this plugin?

I want Prettier to format Liquid templates `onSave` in VSCode. I tried changing [VSCodes's language identifier](https://code.visualstudio.com/docs/languages/identifiers) for `.liquid` files:

```json
"files.associations": {
  "*.liquid": "html"
}
```

This works in the way that Prettier will process those files, but highlighting and auto-completion for Liquid specific syntax breaks.

Instead of telling VSCode to treat `.liquid` files as HTML, the plugin registers Prettier's default HTML parser for the `liquid` language.

## Installation

```sh
npm install -D https://github.com/nicolaibach/prettier-plugin-liquid.git
```

## Usage

> Plugins are automatically loaded if you have them installed in the same `node_modules` directory where `prettier` is located.
>
> –– https://prettier.io/docs/en/plugins.html#using-plugins

## Resources

- [Prettier Plugins Documentation](https://prettier.io/docs/en/plugins.html)
- [Linguist list of languages](https://github.com/github/linguist/blob/master/lib/linguist/languages.yml)

## License

This project is [MIT](https://github.com/nicolaibach/prettier-plugin-liquid/blob/master/LICENSE) licensed.
