
# react-native-react-native-power-optimization-prompt

## Getting started

`$ npm install react-native-react-native-power-optimization-prompt --save`

### Mostly automatic installation

`$ react-native link react-native-react-native-power-optimization-prompt`

### Manual installation

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNReactNativePowerOptimizationPromptPackage;` to the imports at the top of the file
  - Add `new RNReactNativePowerOptimizationPromptPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-react-native-power-optimization-prompt'
  	project(':react-native-react-native-power-optimization-prompt').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-react-native-power-optimization-prompt/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-react-native-power-optimization-prompt')
  	```


## Usage
```javascript
import RNReactNativePowerOptimizationPrompt from 'react-native-react-native-power-optimization-prompt';

// TODO: What to do with the module?
RNReactNativePowerOptimizationPrompt;
```
  