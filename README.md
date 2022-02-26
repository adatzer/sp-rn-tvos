Temporary fork of [snowplow-react-native-tracker](https://github.com/snowplow/snowplow-react-native-tracker) v1.1.0 to test with tvos.


To run the TestAppTvOS:

```
git clone git@github.com/adatzer/sp-rn-tvos.git
cd sp-rn-tvos
npm install
npm run build

cd TestAppTvOS
yarn
cd ios && pod install && cd ..

npx react-native run-ios --simulator "Apple TV" --scheme "TestApp-tvOS"
```
