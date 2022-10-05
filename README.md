# node-project-config
Packages with configurations to various Node project tools all aimed to standardize Node package management.

## Usage

### Prettier
Add the following to your `package.json` file:
```
{
    "prettier": "@svile/prettier-config",
}
```

### ESLint
Add the following to your `package.json` file:
```
{
    "eslintConfig": {
        "extends": "@svile/eslint-config",
        "root": true
    }
}
```

### Jest
Create a `jest.config.js` file in the root directory of your repo with the following contents:
```
module.exports = {
  ...require('@svile/jest-config'),
};

```

### TypeScript
Create a `tsconfig.json` file in the root directory of your repo with the following contents:
```
{
    "extends": "@svile/typescript-config/tsconfig.json",
    "compilerOptions": {
        "baseUrl": "."
    }
}
```

## Customization

Each tool's configuration can be further customized as per the corresponding tool's documentation
