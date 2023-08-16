# React
#### Terminal
```
$ npm install gh-pages --save-dev
```
#### `package.json`
Add above `"name": "project-name",`
```
"homepage": "https://username.github.io/repository-name",
```

Add into `"scripts"`
```
"predeploy": "npm run build",
"deploy": "gh-pages -b gh-pages -d build"
```

#### Terminal
```
$ npm run deploy
```
