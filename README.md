# angular.json
```
"deploy": {
  "builder": "angular-cli-ghpages:deploy",
  "options": {
    "baseHref": "/<repository name>/"
  }
}
```

# Terminal
```
npm i angular-cli-ghpages --save-dev
ng build --base-href=/<repository name>/
npx angular-cli-ghpages --dir=dist/<repository name>
```
