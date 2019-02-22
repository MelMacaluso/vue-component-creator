# Vue component creator

A small boilerplate that automates the creation of components.

## Requirements

As it is built around `vue-cli-service` and it's `lib` option the Vue CLI is a requirement.

```bash
npm i -g @vue/cli
```

## From git clone to fully fledged Vue component NPM package

1.  `git clone git@github.com:MelMacaluso/vue-component-creator.git your-folder`
2.  `cd your-folder`
3.  Delete old remote and set yours `git remote remote origin && git remote add origin <your github repo url>`
4.  Set the upstream so that you can push to your repo `git push -u origin master`
5.  Install packages `npm i`
6.  Edit `package.json` with your meta info
7.  Start the hot reloading server `npm run serve`
8.  "_Happy_" coding 😎(😭)
9.  When done `npm run build`
10. Deploy patch/minor/major to NPM and push to your github repo the version tags `npm run publish-<patch/minor/major>`
11. Don't forge to also `git push` if you want to update your repo accordingly

## Features

- [x] Hot reload
- [x] Easy prototyping with scss bundled in and basic folder structure
- [x] No messing around with package.json settings or vue.config.js madness
