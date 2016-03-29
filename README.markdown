# Bike Index shopify theme

-------

The Bike Index shop uses [Timber scaffolding](http://shopify.com/timber) for a base.

It draws inspiration from [GitHub's shop](https://github.myshopify.com/).

```
├── assets
│   └── Javascript, CSS, and theme images
├── layout
│   ├── theme.liquid
├── snippets
│   └── custom code snippets
├── spec
│   └── tests and helpers
├── templates
│   ├── 404.liquid
│   ├── article.liquid
│   ├── blog.liquid
│   ├── cart.liquid
│   ├── collection.liquid
│   ├── collection.list.liquid
│   ├── index.liquid
│   ├── list-collections.liquid
│   ├── page.contact.liquid
│   ├── page.liquid
│   ├── product.liquid
│   ├── search.liquid
│   └── customers
│         └── required templates if customer accounts are enabled
├── config.yml
│   └── Setup for the [Theme Gem][2]
```

i18n testing
---------------------
Tests make sure there are no missing or extra i18n strings or invalid html in your locale liquid files.

All PRs must pass the tests before being merged. Check the test status when you open a new PR on GitHub, or locally with the following.

- `bundle install` to install all the dependecies
- `rspec spec` to run all the tests

Additional resources
---------------------
- [Thoughtbot on shopify theme dev][0]: Useful hints on shopify theme development in 
- [Themes Documentation][1]: Learn more about Liquid and theme templates.
- [Theme Gem][2]: Run the command line for a more intimate way of managing your theme files.
- [Theme Kit][7]: Next generation tool for syncing theme files. Currently in beta.
- [Liquid Tag Cheat Sheet][4]

License
---------------------
The Bike Index shopify theme is released under the [MIT License](LICENSE)

[0]: https://robots.thoughtbot.com/shopify-theme-development
[1]: http://docs.shopify.com/themes
[2]: https://github.com/Shopify/shopify_theme
[3]: http://apps.shopify.com/desktop-theme-editor
[4]: http://cheat.markdunkley.com
[5]: https://www.shopify.com/retailtour
[6]: http://ecommerce.shopify.com/c/ecommerce-design
[7]: https://github.com/Shopify/themekit
