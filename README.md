#amd-ninja
for simple amd load script, but I think it may be a powerful loader.<br/>

##to jsers:
this is a very easy lib compared with requirejs and other amd loaders, but it is new, need your effort to make it more powerful.

###usage:
the same usage as requirejs, but need your commit to complete the other plugins which already exists in requirejs loader.

###time for loading:
nearly the same as requirejs, but slower than requirejs a little,<br>
so, I need your help to resolve the loading time and keep loadings the right <br>
order. <br>
I tried many ways to tackle asynchronously running loading tasks, but <br>
failed, if there is some way to fix this problem, this loader will be more <br>
graceful.

###apis

####load deps
require({Array}||{url}, callback);<br/>
but this will not guarantee complete domReady with these loadings togerther,

####ready
require.ready(callback);<br/>
a promise to fired after domReady and your deps loaded

####setBaseDir
require.setBaseDir({dirname});<br/>
set the base dir for loadings

#####adivice:
read the source codes, I think you will quickly hold the idea of mine and grasp the methods.



