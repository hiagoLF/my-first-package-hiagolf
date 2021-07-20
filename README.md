# My First NPM Package

First package to be published on npm

```bash
# tranpile and compile
yarn build

# testing code
yarn start

# Enable this package to be tested on other project on local machine
yarn link

# Import this packge in other project
yarn link "my-first-package-hiagolf"

# The developing package to be tested need to use the same react of
# project where you are testing the package. Then, inside the deleloping
# package, link the react of that project.
npm link ../../react-examples/examples-tests/node_modules/react

# Login on NPM account
npm login

# Publish your package
npm publish
```

-  Only `dist` folder will be installed for user of my package

-  Inspiration: https://blog.logrocket.com/the-complete-guide-to-publishing-a-react-package-to-npm/
