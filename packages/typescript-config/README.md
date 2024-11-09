# `@silx/typescript-config`

## Installation

To install `@silx/typescript-config`, run the following command:

```sh
$ npm install @silx/typescript-config --save-dev
```

## Usage

Extend `@silx/typescript-config` and any additional configurations in your `tsconfig.json`:

```json
{
  "extends": "@silx/typescript-config/no-dom/tsconfig.monorepo.json",
  "compilerOptions": {
    "module": "NodeNext",
    "moduleResolution": "NodeNext",
    "jsx": "react-jsx",
    "outDir": "dist"
  },
  "include": ["src"],
  "exclude": ["node_modules", "dist"]
}
```
