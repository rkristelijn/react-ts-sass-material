My goal is to set up a React boilerplate example using the common tools:

| tool/platform/library/framework                                                      | why                         |
| ------------------------------------------------------------------------------------ | --------------------------- |
| [create-react-app](https://facebook.github.io/create-react-app/docs/getting-started) | consistent folder structure |

# Plan

## Phase 1

- [x] Create a boilerplate with just React and typescript
  - [x] fix 16289 vulnerabilities found - Packages audited: 888779 [#1](https://github.com/rkristelijn/react-ts-sass-material/issues/1)
  - [ ] WARNING: You are currently running a version of Typescript which is not officially supporter by typescript-estree [#3](https://github.com/rkristelijn/react-ts-sass-material/issues/3)
- [x] Add sass support [#2](https://github.com/rkristelijn/react-ts-sass-material/issues/2)
- [x] Fix prettier issues [#5](https://github.com/rkristelijn/react-ts-sass-material/issues/5)
- [ ] Add material.io support [#6](https://github.com/rkristelijn/react-ts-sass-material/issues/6)
- [ ] Rebuild [the example](https://material-ui.com/getting-started/templates/dashboard/), [my example](http://gius.nl/material) [github project](https://github.com/rkristelijn/react-material-ui) [#7](https://github.com/rkristelijn/react-ts-sass-material/issues/7)

## Phase 2

- [ ] Move src to src/front
- [ ] Include node with typescript support in src/back
- [ ] Build in public folder of src/back and be able to run the app with only the backend server running
- [ ] have a shared code lib

## Phase 3

- [ ] Set up REST API
- [ ] Integrate backend calls (using axios? and jsend?)

# Sources

| source                                                                                                                                                                               | what to find                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------- |
| [Using SASS Modules In Create React App V2](https://medium.com/@shalomdave2/using-sass-modules-in-create-react-app-v2-306950fd8e99) - Shalom David                                   | Configure sass in react and improve the example |
| [Create React App with TypeScript, Sass & Material UI](https://medium.com/@bhattacharyya.abhra/create-react-app-with-typescript-sass-material-ui-5a22730f6cae) - Abhra Bhattacharyya | Integrate sass, material, ts and react          |
| [Create React App](https://facebook.github.io/create-react-app/docs/documentation-intro) documentation                                                                               | Info right from the source                      |
| [Client, Server and Shared code](https://medium.com/front-end-weekly/client-server-and-shared-code-846097c5260e) - Gil Amran                                                         | Share code with back/front                      |
| [Material.io Web Developer tutorials](https://material.io/collections/developer-tutorials/#web)                                                                                      | Tutorials                                       |
