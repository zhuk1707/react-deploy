# How To Deploy React App

`git inint`

`git status`

`git add .`

`git commit -m "initial commit"`

`git branch -M 'main`

`git remote add origin "URL"`

`git push -u origin 'main'`

`npm install gh-pages --save-dev`

In _package.json_ add:

* "homepage" : "https://_username_.github.io/_app-name_"

* "predeploy":"npm run build"

* "deploy":"gh-pages -d build"

`npm run deploy`