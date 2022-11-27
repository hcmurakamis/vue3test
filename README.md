# vue3test
Vue3+TS+Vuetify3+Jest runnable minimum code

# Envrieonment
 - ubuntu 20.4.15 LTS(on Win10 on bootcamp)
 - node 16.8.1
 - yarn 1.12.19
 - sudo su

# How to recreate
## 1. Install yarn
 - curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash
 - source ~/.bashrc
 - nvm install 16
 - nvm use 16
 - curl -o- -L https://yarnpkg.com/install.sh | bash
 - source ~/.bashrc
 
## 2.Install vue cli, project and vuetify
 - yarn global add @vue/cli
 - vue create minimum
   - ? Please pick a preset: Manually select features
   - ? Check the features needed for your project: Babel, TS, Linter, Unit
   - ? Choose a version of Vue.js that you want to start the project with 3.x
   - ? Use class-style component syntax? Yes
   - ? Use Babel alongside TypeScript (required for modern mode, auto-detected polyfills, transpiling JSX)? Yes
   - ? Pick a linter / formatter config: Basic
   - ? Pick additional lint features: Lint on save
   - ? Pick a unit testing solution: Jest
   - ? Where do you prefer placing config for Babel, ESLint, etc.? In package.json
   - ? Save this as a preset for future projects? No
 - cd minimum
 - vue upgrade
 - vue add vuetify
   - ? Choose a preset: Vuetify 3 - Vue CLI (preview)
    