# `silx/jest-config`

## Installation

To install `silx/jest-config`, run the following command:

```sh
$ npm install silx/jest-config --save-dev
```

## Usage

Extend `silx/jest-config` and any additional presets in your `jest.config.ts`:

```ts
import sharedJestConfig from "silx/jest-config/browser/jest.config.browser";
import type { Config } from "jest";

const jestConfig: Config = {
  ...sharedJestConfig,
  setupFilesAfterEnv: ["<rootDir>/jest.setup.ts"],
};

export default jestConfig;
```
