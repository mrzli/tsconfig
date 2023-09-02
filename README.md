# TSConfig

A shared TypeScript configuration for my projects.

## Installation

```bash
npm install --save-dev @gmjs/tsconfig
```

## Usage

Just extend it in your project's `tsconfig.json`, for example:

```json
{
  "extends": "@gmjs/tsconfig"
  "compilerOptions": {
    "outDir": "./dist"
  }
}
```
