# get-nps

A solution for get npm package size **before** download and install with travis-ci!

## How get npm package size?

Note: if you use get-nps with **fork** first set up get-nps in your [travis-ci](https://travis-ci.org/) and enable get-nps.

for make get-nps package and get npm package size in travis, following down methods:  
for example get-nps _angularJs_

1. Edit [`.travis.yml`](https://github.com/xtoolkit/get-nps/edit/master/.travis.yml) (suggested in my repo) and create a pull. 
2. Go to travis link in your pull page.
3. See travis logs and get-nps details!

## Explain for angularJs demo

1. Edit [`.travis.yml`](https://github.com/xtoolkit/get-nps/pull/7/files#diff-354f30a63fb0907d4ad57269548329e3R9) and create [#7 Demo for angular/angular.js](https://github.com/xtoolkit/get-nps/pull/7) pull.
2. Go to [partial](https://github.com/xtoolkit/get-nps/pull/7#partial-pull-merging) pull.
3. Go first [details travic-cl link](https://travis-ci.org/xtoolkit/get-nps/builds/198417685) and see details!
  - [git size in disk](https://travis-ci.org/xtoolkit/get-nps/builds/198417685#L268)
  - [source size in disk](https://travis-ci.org/xtoolkit/get-nps/builds/198417685#L272) (remove .git dir)
  - [source size in disk after npm install](https://travis-ci.org/xtoolkit/get-nps/builds/198417685#L282)
  - [all deps downloaded](https://travis-ci.org/xtoolkit/get-nps/builds/198417685#L290) (sum tgz)
