gradle-workshop
===============
tim just wrote a short book for o'reilly on gradle
older book is for free on gradleware

adding support for builds for .net c/c++, ios, js

ant
---
imperative, steps called targets
doesn't do a good job to hide complexity

maven
-----
declarivitve
fill out a form

gradle
------
imperivite but can drop back and be declaravite
a build is software


finds sources in etc etc automatically
imperative code should mainly be in plugins, not directly in the build.gradle

rules
-----
groove meta programming

dependencies
------------
can pull from various repos 
* maven
* artifactory
* ivy
* static lib dir
* mix them all together

wrapper
-------
gradlew
	will control what version of gradle the build is run with
	./gradlew <name>
	
tasks are normally camel case
* if you do you can abbreviate - fooBar -> fB

buildscript
-----------
these will be loaded for the build itself

liqui base
==========
puts your schema into source control
changelog - ordered lists...
**	changeset
***	refactoring - actual schema changes
database keeps meta data to know which change sets have been applied to db

checkout
========
sublime text 2 - cross platform instead of notepad++