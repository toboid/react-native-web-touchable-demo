# react-native-web-touchable-demo

> Demo project showcasing an exception when using React Native Web Touchable component.

## Getting started

* Install dependencies

```bash
yarn
```

* Run the tests

```bash
yarn test
```

**Expected** snapshots to be created.

**Actual Result**

```
TypeError: this._touchableNode.addEventListener is not a function

      at Object.componentDidMount (node_modules/react-native-web/dist/components/Touchable/Touchable.js:1:5432)
      at Object.<anonymous> (index.test.js:8:1)
          at new Promise (<anonymous>)
          at <anonymous>
      at process._tickCallback (internal/process/next_tick.js:188:7)
```
