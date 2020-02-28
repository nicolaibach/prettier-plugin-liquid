# prettier-plugin-liquid

[Prettier](https://prettier.io) plugin to make Prettier parse [Liquid](https://github.com/Shopify/liquid) files as HTML.

This plugin doesn't provide any special formatting for the Liquid markup language!

## Why this plugin?

I want Prettier to format Liquid templates `onSave` in VSCode. I tried changing [VSCodes's language identifier](https://code.visualstudio.com/docs/languages/identifiers) for `.liquid` files, but then I loose syntax highlighting and auto-completion provided by other plugins:

```json
"files.associations": {
  "*.liquid": "html"
}
```

## Resources

- [Prettier Plugins Documentation](https://prettier.io/docs/en/plugins.html)
- [Linguist list of languages](https://github.com/github/linguist/blob/master/lib/linguist/languages.yml)

## License

This project is [MIT](https://github.com/nicolaibach/prettier-plugin-liquid/blob/master/LICENSE) licensed.
