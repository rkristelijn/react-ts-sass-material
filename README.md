My goal is to set up a React boilerplate example using the common tools:

| tool/platform/library/framework                                                      | why                         |
| ------------------------------------------------------------------------------------ | --------------------------- |
| [create-react-app](https://facebook.github.io/create-react-app/docs/getting-started) | consistent folder structure |

# Plan

## Phase 1

- [ ] Create a boilerplate with just React and typescript
  - [ ] fix 16289 vulnerabilities found - Packages audited: 888779 [#1](https://github.com/rkristelijn/react-ts-sass-material/issues/1)
- [ ] Add sass support
- [ ] Add material.io support
- [ ] Rebuild [the example](http://gius.nl/material) [github project](https://github.com/rkristelijn/react-material-ui)

## Phase 2

- [ ] Move src to src/front
- [ ] Include node with typescript support in src/back
- [ ] Build in public folder of src/back and be able to run the app with only the backend server running
- [ ] have a shared code lib

## Phase 3

- [ ] Set up REST API
- [ ] Integrate backend calls (using axios? and jsend?)
