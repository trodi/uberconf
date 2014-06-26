# take aways + notes

## CI
* add ci jobs for our plugin
* add code coverage to ci
	* java - http://cobertura.github.io/cobertura/
	* js - https://github.com/es-analysis/plato
* fail build if threshold of pmd etc. (can we fail if rule ignore override?)
* start with static analysis before compilation -- faster to fail build
	* e.g., pmd -> checkstyle -> compile -> tests -> findbugs

## other
* build installer to allow for easier decoupled deployment
* work angular into client