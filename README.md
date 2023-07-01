# Ivo's ESLint config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;
- Import Sort

## Setup

1. Install the dependencies
```
npm i -D eslint @ivopr/eslint-config
```

2. Create a `.eslintrc.json` file extending the config:
```
{
  "extends": "@ivopr/eslint-config/react"
  // "extends": "@ivopr/eslint-config/node"
}
```

> You can also use a `.eslintrc.js` instead of JSON if you prefer.
