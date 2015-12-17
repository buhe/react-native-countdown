## react-native-countdown

A <CountDown> component for react-native

### Add it to your project

Run `npm install react-native-countdown --save`

```javascript
// Within your render function. Count down after press it.
<CountDown
  onPress={this.sendAgain} //default null
  text={'Try again'} //default ''
  time={60} //default 60
  buttonStyle={{padding:20}}
  textStyle={{color:'black'}} //default black
  disabledTextStyle={{color:'gray'}} //default gray
/>
```
## TODOS

- [x] Add custom style
