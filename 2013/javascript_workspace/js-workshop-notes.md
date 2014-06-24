javascript-workshop
===================

book - javascript, the good parts
'==' is js use type corersion if possible
'===' tells js not to use corersion
array isn't primative - can't compare arrays or any objects as objects
arrays are objects!
variadic: arbitrary number of parameters to a function
anonymous functions
no function overloading, if you define multiple, the last is the only one created
hoisting - ppl declare all vars at top of scope to avoid hoisting issues, js interpreter moves all to top anyways
parse phase then execute phase
access array -- arguments[arg], makes associated array/map 0: val, 1: val2
function
	this, arguments, named parameters
object is defined by 'function' keyword
you can monkey with any object/member var at anytime, all public accessible
typescript and coffeescript compile down to js
DUCK TYPING!!!


prototype
---------
prototype means its the the parent's property. class heiarchy
iphone.__proto__.describe() --instance
class.prototype.describle() --class
...apply() -- apply will supply the context for 'this'

inheritance
-----------
parisitic inheritance
don't need and shouldn't "new" objects, bc using factory functions
many frameworks use this, but he suggests avoiding this

iefc - immediately execute function call
	for scope safety

JSON Parsing
------------
taffy.db
some stuff in underscore.js

testing
-------
BDD framework - jasime
http://pivotal.github.io/jasmine/

underscore.js
=============
like java's guava





Questions
=========
-why choose js when there are so many inconsistencies that allow you to shoot yourself in the foot?
it's ubiquitos, ppl didn't take it seriously, now standards are planning on updating some things, adding true meta programming
-why is js gaining in such popularity for server side? startup etc?
node.js has very small good usecase -> simple tasks that need to scale, general purpose webapp should choose something else