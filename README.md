# my-first-package-hiagolf

First package to be published on npm

```
yarn build // tranpile and compile
yarn start // testing code
yarn link // Enable this package to be tested on other project on local machine
yarn link "my-first-package-hiagolf // Import this packge in other project

// The developing package to be tested need to use the same react of
// project where you are testing the package. Then, inside the deleloping
// package, link the react of that project.
npm link ../../react-examples/examples-tests/node_modules/react
```

-  Only `dist` folder will be instaled for a user of my package
