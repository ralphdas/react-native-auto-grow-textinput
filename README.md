# ReactNative Auto Grow TextInput

<a href="https://www.npmjs.com/package/react-native-auto-grow-textinput"><img src="https://img.shields.io/npm/v/react-native-auto-grow-textinput.svg"></a>

This component allows to create auto grow text input for both platforms (iOS and Android).

## Getting started
First of all, you need to install `react-native-auto-grow-textinput` to your project.

```
$ yarn add react-native-auto-grow-textinput
```

After, you can use it in your project:

```javascript
import { AutoGrowTextInput } from 'react-native-auto-grow-textinput';

...
// If you don't need max height
<AutoGrowTextInput placeholder='Some text here' />
// else if you need to set up max height
<AutoGrowTextInput placeholder='Some text here' maxHeight={ 120 } />
...
// Also you can use any other TextInput props with AutoGrowInputText component
```

I hope it'll save your time.
