# react-native-style-guide

## Install VsCode eslint plugin

## Install eslint locally

`yarn add eslint -D`

## Install eslint-config-airbnb which need few other dependencies as well

`yarn add eslint-config-airbnb eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-react -D`

## Install prettier and related dependencies

`yarn add prettier eslint-config-prettier eslint-plugin-prettier -D`

## Create .eslintrc file in the root directory and add the following code

`{ "extends": [ "airbnb", "prettier", "prettier/react" ], "rules": { "react/jsx-filename-extension": [ 1, { "extensions": [ ".js", ".jsx" ] } ], "prettier/prettier": [ "error", { "trailingComma": "es5", "singleQuote": true, "printWidth": 100 } ] }, "plugins": [ "prettier" ] }`

## Add following lines to user settings

`{ "editor.formatOnSave": true, "[javascript]": { "editor.formatOnSave": false }, "editor.codeActionsOnSave": { "source.fixAll.eslint": true }, "eslint.alwaysShowStatus": true, }`
