to see the issue:
```
yarn install
yarn tsc
```

to test the solution, change `node_modules/@types/bn.js` to use `export default BN` instead of `export = BN`
