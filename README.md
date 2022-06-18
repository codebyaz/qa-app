# the QA app
Address QA artifacts, tests practices using jest and Cypress while CI using GitHub actions and more.

*general statement: this document is considering an expo project typed with typescript

## sections
*general statement: this document is considering an expo project typed with typescript

- [X] fundamentals and best practices

### fundamentals
- [ ] project structure
- [ ] commit patterns: https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716
  #### QA artifacts
  - [ ] design: https://www.figma.com/
  - [ ] specification: ADD
  #### smoke tests

### test environment setup
#### libraries
Install Jest using yarn:

yarn add --dev jest
Or npm:

npm install --save-dev jest
https://github.com/facebook/jest#getting-started

Using yarn
yarn add --dev @testing-library/react-native
Using npm
npm install --save-dev @testing-library/react-native
https://github.com/callstack/react-native-testing-library#installation

npm install --save-dev @testing-library/react-hooks
https://github.com/testing-library/react-hooks-testing-library#installation

npm install -D fetch-mock-jest
https://github.com/wheresrhys/fetch-mock-jest#installation

npm i --save-dev jest-date-mock
https://github.com/hustcc/jest-date-mock#install


  - [ ] Configuration files (jest.config.js and others)
  
#### Unit + E2E
  - [ ] Cypress library
### IDE configuration
https://www.notion.so/Instala-o-das-ferramentas-2e3f74b481204a69a1189a4cfe54adc7
https://www.notion.so/Instala-o-das-ferramentas-2e3f74b481204a69a1189a4cfe54adc7#e439b97761b74910a6cca3a2852bcbd2
### CI
  #### GitHub actions
  - [ ] Cypress: https://www.youtube.com/watch?v=m0dAL83rnRc&list=PLP9o9QNnQuAZ3xPxrPx1cgFj2GvY1-vq3&index=1
### CD
  - [ ] Code Push
### Monitoring
  - [ ] Sentry application
### Practices
#### file nomenclature
componentName.spec.tsx
#### file placement

#### test recipe
```
it('should .....', () => {
  ..... arrange
  ..... act
  ..... assert
});
```
#### test template
```
..... native and third part imports
..... internal imports
..... general mocks
```

<details><summary>example</summary>
```
  code here
```
</details>
