# TypeScript config

## Installation

```shell
pnpm add -D @norniras/ts-config
```

## Usage

Inside **tsconfig.json** add:

```json
{
  "extends": ["@norniras/ts-config/base.json"],
  "compilerOptions": {
    "baseUrl": ".",
    "outDir": "dist",
  },
  "include": [
    "src/**/*.ts",
  ]
}
```