# 3630test

This app is a demonstration of using create-react-app with react-router and deploying on github-pages

# steps performed

1. Created a new app using `create-react-app 3630test`
2. Created components, added router code using hashHistory instead of browserHistory
3. Created a github repo and pushed first commit
4. Added a `homepage` attribute to the package.json file `"homepage": "https://mdjasper.github.io/3630test"`
5. Added `gh-pages` package by running `npm install --save-dev gh-pages`
6. Added scripts to package.json `"predeploy": "npm run build", "deploy": "gh-pages -d build"`
7. Ran `npm run deploy`
8. Ensured that the `gh-pages` branch was set as the branch to use in the github settings page

You can visit the deployed app at [https://mdjasper.github.io/3630test](https://mdjasper.github.io/3630test)