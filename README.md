Ace (Ajax.org Cloud9 Editor)
============================

Ace is a code editor written in JavaScript, forked and customized for ease of
inclusion with private automated header generation mechanism in an AngularJS
project.

This repository has only generated files.
- If you want to work on ace please go to https://github.com/ajaxorg/ace
- If you want access to the full 4 build distros go to https://github.com/ajaxorg/ace-builds 

This branch contains private pruned fork of the src-min-noconflict distro
with a working valid private 'bower.json' such that bower install 
works **PROPERLY** and src inclusion can be automated through analysis
of the bower.json files of included modules rather than tedius, suboptimal
manual inclusion.

 * [src-min-noconflict](https://github.com/ajaxorg/ace-builds/tree/master/src-min-noconflict)
 
Use:
```
$ bower install git@github.com:gmsewell6/ace-builds.git#dev-ace-builds --save
```
