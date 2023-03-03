# Shared TS configuration for libraries

Usage:

```
npm i -D @cloud-cli/typescript-config
```

`tsconfig.json`:

```json
{
  "extends": "@cloud-cli/typescript-config",
  "compilerOptions": {
    "outDir": "./dist"
  },
  "include": ["./src/**/*.ts"]
}
```
