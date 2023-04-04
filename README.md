# @planetscale/core-prettier

PlanetScale's shared [Prettier](https://prettier.io) configuration including tailwind-prettier.

## Usage

**Install**:

```sh
$ npm install --save-dev prettier prettier-plugin-tailwindcss @planetscale/core-prettier
```

**Edit `.package.json`**:

```javascript
// ...

"prettier": "@planetscale/core-prettier",

// ...

```

[Read more on sharing configurations](https://prettier.io/docs/en/configuration.html#sharing-configurations).

## Releasing

Create a [Personal Access Token (classic)](https://github.com/settings/tokens) with the `write:package` scope and log into npm with that token [(per GitHub docs)](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-npm-registry#authenticating-with-a-personal-access-token):

```shell
$ npm login --scope=@planetscale --auth-type=legacy --registry=https://npm.pkg.github.com

> Username: USERNAME
> Password: TOKEN
```

Run the `postpublish` script with `$ npm run postpublish`.
