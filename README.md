# ESLint Config

Unified ESLint configuration preset

## Packages

- eslint-config: default config preset
- eslint-plugin:
  - esnext: basic config
  - vue: vue support
  - json: parse json + package.json sort
  - yml: parse yml
  - typescript: typescript support
  - typescript-type-checking: typescript type checking

## Development

```bash
# Install pnpm
npm i -g pnpm

# Install deps
pnpm i
```

## Using

```bash
# Install
pnpm i @antongospod/eslint-config -D

# Add to your .eslintrc config
{
  "extends": "@antongospod"
}

## License

MIT License © 2023 [Anton](https://github.com/antongospod)
