# tsconfig

Shared [TypeScript config](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html)

See [tsconfig](./tsconfig.json)

## Install

```bash
npm install --save-dev @yuler/tsconfig
```

## Usage

tsconfig.json

```json
{
  "extends": "@yuler/tsconfig",
  // overwrite
  "compilerOptions": {
    "outDir": "dist"
  }
}
```

## Inspire by

- [tsconfig](https://github.com/sindresorhus/tsconfig)
