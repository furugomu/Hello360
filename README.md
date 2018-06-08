# Hello360

```console
$ npm install -g react-360-cli
$ react-360 init Hello360
$ cd Hello360
$ git init
$ git remote add origin git@github.com:furugomu/Hello360.git
$ git add -A
$ git commit -m Hello360
$ git remote add origin git@github.com:furugomu/Hello360.git
$ git push -u origin master

$ npm run bundle
$ cd build
$ cp -a ../index.html ../static_assets .
$ vi index.html # *.bundle?platform=vr -> *.bundle.js
$ git init
$ git checkout -b gh-pages
$ git add -A
$ git commit -m 'bundle'
$ git remote add origin git@github.com:furugomu/Hello360.git
$ git push -u origin gh-pages
```
