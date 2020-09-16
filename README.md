**About**

This repository contains settings template for ESlint and Prettier for JavaScript coding.

**How to use**

1. Copy `/.vscode`, `.eslintrc.json` and `prettierrc.json` to your project.
2. Add this block to dependencies in `package.json`:

```
"react-scripts": "3.4.3",
"babel-eslint": "^10.0.3",
"eslint": "^6.8.0",
"eslint-config-babel": "^9.0.0",
"eslint-config-prettier": "^6.10.0",
"eslint-plugin-import": "^2.20.0",
"eslint-plugin-prettier": "^3.1.2",
"eslint-plugin-react": "^7.18.0",
"eslint-plugin-standard": "^4.0.1",
"prettier": "^1.19.1"
```

3. Remove from `package.json`:

```
"eslintConfig": {
  "extends": "react-app"
},
```

4. `npm install`
