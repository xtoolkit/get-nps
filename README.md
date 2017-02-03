# get-nps

A solution for get npm package size **before** download and install with travis-ci!

## How make a get-nps?

1. Edit [`.travis.yml`](https://github.com/xtoolkit/get-nps/edit/master/.travis.yml) in my repo and create a pull. 
2. Go to travis link in your pull page.
3. Go end line in travis logs and see your npm package installed size!
4. and continue life :)

## Example for angularJs

[logs](https://travis-ci.org/xtoolkit/get-nps/builds/197955003) for [angularJs](https://github.com/angular/angular.js) test:

1. [git clone size](https://travis-ci.org/xtoolkit/get-nps/builds/197955003#L278)
2. [node_modules dir size](https://travis-ci.org/xtoolkit/get-nps/builds/197955003#L1728)
3. [Sub npm package size](https://travis-ci.org/xtoolkit/get-nps/builds/197955003#L1737)
