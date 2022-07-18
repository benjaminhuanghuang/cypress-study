## Cypress
- Install
```
npm i -D cypress

yarn add cyress --dev
```

- Open cypress test runner
```
npx cypress open

yarn run cypress open
```

This comman will open cypress GUI and create 

cypress/integration/

cypress.json
```
{
  "ignoreTestFiles": "**/example/*",
  "baseUrl" : "http://localhost:3000",
  "wiewportWidth": 1920,
  "wiewportHeight": 1080

}
```

In VS code, Add .eslintrc.json to cypress directory
```
{
  "extends": [
    "plugin:cypress/recommended"
  ]
}
```