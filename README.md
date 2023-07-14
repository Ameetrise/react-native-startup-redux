# react-native-startup-redux

redux, bottom nav, drawer and component screens all set

## Installation

```sh
npm install react-native-startup-redux
```

##Expexted Usage, under development

## Usage

```js
import { store, sagas, dispatch } from 'react-native-startup-redux';

// ...

const reduxOption: ReducSetupOptions = {
actions:[appStateAction],
reduxers:[appStateReducer],
actionTypes:[AppStateActionTypes],
appState:AppState,
};
```

## Contributing

See the [contributing guide](CONTRIBUTING.md) to learn how to contribute to the repository and the development workflow.

## License

MIT

---

Made with [create-react-native-library](https://github.com/callstack/react-native-builder-bob)
