
# react-native-native-d-pay-library

## Getting started

`$ npm install react-native-native-d-pay-library --save`

### Mostly automatic installation

`$ react-native link react-native-native-d-pay-library`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-native-d-pay-library` and add `RNNativeDPayLibrary.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNNativeDPayLibrary.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNNativeDPayLibraryPackage;` to the imports at the top of the file
  - Add `new RNNativeDPayLibraryPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-native-d-pay-library'
  	project(':react-native-native-d-pay-library').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-native-d-pay-library/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-native-d-pay-library')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNNativeDPayLibrary.sln` in `node_modules/react-native-native-d-pay-library/windows/RNNativeDPayLibrary.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Native.D.Pay.Library.RNNativeDPayLibrary;` to the usings at the top of the file
  - Add `new RNNativeDPayLibraryPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNNativeDPayLibrary from 'react-native-native-d-pay-library';

// TODO: What to do with the module?
RNNativeDPayLibrary;
```
  