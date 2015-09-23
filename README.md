# amd-ninja
for simple amd load script, but I think it may be a powerful loader.

##to jsers: 
this is a very easy lib compared with requirejs and other amd loaders, but it is new, need your effort to make it more powerful.

###usage: 
the same usage as requirejs, but need your commit to complete the other plugins which already exists in requirejs loader.

###time for loading:
nearly the same as requirejs

###apis

####load deps
require({Array}||{url}, callback);
but this will not guarantee complete domReady with these loadings togerther,

####ready
require.ready(callback)
a promise to fired after domReady and your deps loaded

####setBaseDir
require.setBaseDir({dirname});

###adivice: read the source codes, I think you will quickly hold the idea of mine and grasp the methods.



