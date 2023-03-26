# vue-StyleValue-type

Demo Undefined type is complained when bind :style to an arra



## Reproduce steps

```sh
npm install
```

### Type-Check

```sh
npx vue-tsc --noEmit
```

### Error

```ts
src/App.vue:2:17 - error TS2322: Type 'undefined' is not assignable to type 'StyleValue'.

2   <h1 :style="[ style, {background: 'green'} ]">Test</h1>
```
