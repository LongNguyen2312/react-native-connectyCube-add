# ConnectyCube React Native SDK for messaging and video calling apps

[ConnectyCube](https://connectycube.com) React Native SDK.

ConnectyCube is a messaging and video calling platform for iOS, Android, Web, React Native, NativeScript and Cordova apps.

Check our [comprehensive guide](https://developers.connectycube.com/reactnative/) for React Native SDK.

# Additional

* Add signUp function in the app

For more details check the [ConnectyCube features page](https://connectycube.com/features)

# Connect SDK

Simply install the package in a normal way:

```bash
yarn add https://github.com/LongNguyen2312/react-native-connectyCube-add.git
```

and you're ready to go:

```javascript
import ConnectyCube from 'react-native-connectycube'

const credentials = {
    appId: 21,
    authKey: 'hhf87hfushuiwef',
    authSecret: 'jjsdf898hfsdfk'
};

const config = {
    debug: { mode: 1 }
};

ConnectyCube.init(credentials, config);
```

# Contribution

See more information at [CONTRIBUTING.md](.github/CONTRIBUTING.md)

# License

Apache 2.0
