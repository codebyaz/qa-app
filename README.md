# the QA app
Address QA artifacts, tests practices using jest and Cypress while CI using GitHub actions and more.

## sections
*general statement: this document is considering an expo project typed with typescript
### fundamentals
- [ ] project structure
- [ ] commit patterns: https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716
  #### QA artifacts
  - [ ] design: https://www.figma.com/
  - [ ] specification: ADD
### test environment setup
  #### Unit + Integrated
  - [ ] jest library
  - [ ] React native testing library
  - [ ] React hooks testking library
  - [ ] Configuration files (jest.config.js and others)
  ##### Date mock
  - [ ] Jest date mock library
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
