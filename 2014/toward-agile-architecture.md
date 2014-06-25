# Toward Agile Architecture

## broken architecture
* architect makes his pretty diagram and walks away
* code LOC increases (study 2x over 7 years)
	* https://www.ohloh.net/
* software will change/grow over time, must maintain complexity
* the goal of architecture is to reduce irreversibility
	* e.g., designing to be able to swap out the DB
	* make irreversible decision as late as possible (not at the beginning)
* martin fowler - why do we need architects (article)
* software architecture doc -- was what we ''think'' we have
	* need to use a generated version
	* source code is the design (article - by reaves)
	* source code is the definitive architecture
* "building architecture of a church is the only that is similar to software: First you build it and then you pray"

## essence of agility
* core is getting feedback so we can respond to change
* allow for architecture change
* spread it through out the life cycle, push to the right (later)
* need engagement between architect and devs

## paradox
* really just want to create something that is flexible
* but making things more flexible makes things more complicated
* where do we need the flexibility

## all the way down
* need the flexibility at the seems
	* pkg relationships
	* module relationships
	* the api
* module out jars vs just wrap up the whole war
* SOA - if moduled out then your service isn't as ridge, easy to wrap up a new service

## feedback
* the courage to refactor
* feedback via CI - prove it
	* enforce layers (dependency graphs)
	* enforce the min performance (10 _ per sec)
* java-source.net
	* sonar
* generate most documentation (all long living docs)
* generate metrics on module/pkg/etc. structure
* generate visualization