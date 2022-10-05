# TypeScript configuration
All aimed to standardize Node package management.

## Usage
Create a `tsconfig.json` file in the root directory of your repo with the following contents:
```
{
    "extends": "@svile/typescript-config/tsconfig.json",
    "compilerOptions": {
        "baseUrl": "."
    }
}
```
