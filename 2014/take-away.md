# take aways + notes

## CI
* add ci jobs for our plugin
* add code coverage to ci
	* java - http://cobertura.github.io/cobertura/
	* js - https://github.com/es-analysis/plato
* fail build if threshold of pmd etc. (can we fail if rule ignore override?)
* start with static analysis before compilation -- faster to fail build
	* e.g., pmd -> checkstyle -> compile -> tests -> findbugs

## arduino
* http://www.instructables.com/id/Cwik-Clock-v10-An-Arduino-Binary-Clock/step10/Goodbye-Prototype-Hello-Production/
* http://www.reddit.com/r/electronics/comments/19rdr4/how_do_i_go_from_arduino_prototype_to_cheap_mass/

## other
* build installer to allow for easier decoupled deployment
* work angular into client