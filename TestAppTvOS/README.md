TestAppTvOS created using

```
npx react-native init TestApp --template=react-native-tvos@latest
```

Ref: https://github.com/react-native-tvos/react-native-tvos

Also inside the TestAppTvOS dir, the e2e test are included from the DemoApp, with some modifications.

The e2e tests won't run. Only `yarn test` can run and should fail, unless someone spins up Micro on port 9090 and manually simulates the user journey as in `emitEvents.e2e.detox.js`.

To see the tests diff:

```
diff --recursive TestApp/tests DemoApp/tests
```
