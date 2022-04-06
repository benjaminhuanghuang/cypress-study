## Cypress
Install
```
npm i -D cypress
```

Open cypress GUI
```
npx cypress open
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