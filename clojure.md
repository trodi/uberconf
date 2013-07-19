clojure
=======
* address outdated "yesterday's assumptions"
* functional language
* dyanmically typed
* designed to be moved to other platforms
* ultimately is a new _lisp_
* ignores ',' takes out all commas and semi-colons
* never ambiguity in persidence 
* built in documentation notion (like javadoc)
* just namespaces and functions (no classes)
* can call java functions (inter op)
* lots of general functions, few data structures
* lazy by default
claims high performance computing
* use for concurrency and big data
* hadoop ... cacalog?

functional
----------
* easier to test
* easier to compose
* essential at scale (multi core)
* difference btw building out of bricks and sand with wind blowing

if not order dependent, but uses order, it is over specified 

edn - extensible data notation
------------------------------
* way of transfer of _values_
* impl of all the basic data types
* extension model
* was taken out of clojure to be used elsewhere too

functions
---------

### operators
functions with funny names
```clojure
(+ 1 2 3 4)```

namespace
---------
```clojure
(ns com.exmaple.foo
	(:require 
	 [clojure.data.generators :as gen]))
```
can add meta data - first class citizen unlike javadoc

vectors
-------
* []
* insert at rear

protocols
---------
no impl, act like interfaces

apparently devs produce the same LOC per day no matter the language so more expressive language means more work

resources
---------
* clojure docs
* clo-jars
* prismatic - AI news...
* 