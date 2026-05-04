# GeeSome apiDoc Template

Modern apiDoc template package for GeeSome API documentation.

This template targets `apidoc@1.x`, which expects custom templates to provide:

- `template/index.html`
- `template/src/webpack.config.js`
- `template/src/main.js`
- `template/src/css/main.css`
- `template/fonts`
- `template/img`

The old vendored `template/vendor`, root `template/main.js`, and generated `api_data.js` layout is intentionally not used anymore.

## Usage

```sh
yarn add -D apidoc geesome-apidoc-template
apidoc -i ./examples -f .route.js -o ./docs -t ./node_modules/geesome-apidoc-template/template
```

For this repository:

```sh
yarn install
yarn smoke
```

![Demo screenshot](https://raw.githubusercontent.com/ahmed-dinar/apidoc-template/master/examples/assets/Screenshot1.png)

![Demo screenshot](https://raw.githubusercontent.com/ahmed-dinar/apidoc-template/master/examples/assets/Screenshot2.png)

![Demo screenshot](https://raw.githubusercontent.com/ahmed-dinar/apidoc-template/master/examples/assets/Screenshot3.png)

