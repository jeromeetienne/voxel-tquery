# voxel-tquery

tquery.js for voxel.js

### install it

```
npm install voxel-tquery
```

## API

### create a tQuery world

```
var world = require('voxel-tquery').initWorld(game);
```

## license

MIT

## Usefull Command Lines

* to install dev dependancy
```
npm install
```

* to publish the package in npm repo - dont forget to bump version number
```
npm publish
```

* to get a live server of the demo
```
npm start
``` 

* to publish on gh-pages
```
  # go on gh-pages branch
  git checkout gh-pages
  
  # merge master branch
  git merge master
  
  # install all dependancies (if not already done)
  npm install
  
  # force to add them (they are in .gitignore)
  git add -f node_modules
  
  # push it to github
  git push 
  
  # come back on master branch
  git checkout master
```
