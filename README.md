# prettier-config

My personal Prettier configuration, more details are [prettier.io#sharing-configurations](https://prettier.io/docs/en/configuration.html#sharing-configurations).

## How to use?

### 1. Install package.

```sh
yarn add @sqrtthree/prettier-config -D
# OR npm install @sqrtthree/prettier-config -D
```

### 2. Config to use it.

Add the following configuration to your `package.json`:

```json
{
  "name": "YOUR_NAME",
  "version": "YOUR_VERSION",
  "prettier": "@sqrtthree/prettier-config"
}
```

OR config it in `.prettierrc`:

```
"@sqrtthree/prettier-config"
```
