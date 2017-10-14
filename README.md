# react-keys-warning
Repo to reproduce the "each child should have a unique key prop" error in react v16

As reported in React issue #11222: https://github.com/facebook/react/issues/11222

## Steps to reproduce
1. Open `test.html`
2. Open JS console
3. See error text:
```
test.compiled.js:1551 Warning: Each child in an array or iterator should have a unique "key" prop. See https://fb.me/react-warning-keys for more information.
    in span
```

### To recompile JS
```bash
npm run build
```
