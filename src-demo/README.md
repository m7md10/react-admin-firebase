An example project for the [react-admin-firebase](https://github.com/benwinding/react-admin-firebase) package.

# Demo
Try the [demo here!](https://react-admin-firebase-1.web.app)

```
username: test@example.com
password: test@example.com
```

# Get started
You need to add the private Firebase connection file: `src/FIREBASE_CONFIG.js` with the following format from firebase:

``` js
export const firebaseConfig = {
  apiKey: "aaaaaaaaaaaaaaaaaaaaaaaaaaa",
  authDomain: "aaaaaaaaaaaaaaaaaaaaaaaaaaa",
  databaseURL: "aaaaaaaaaaaaaaaaaaaaaaaaaaa",
  projectId: "aaaaaaaaaaaaaaaaaaaaaaaaaaa",
  storageBucket: "aaaaaaaaaaaaaaaaaaaaaaaaaaa",
  messagingSenderId: "aaaaaaaaaaaaaaaaaaaaaaaaaaa",
};
```

Don't forget to add the `export` infront of the configuration that Firebase gives you!

Then just run `npm run start`
