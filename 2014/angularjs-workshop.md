# AngularJS Workshop

* create speakers route
* create views
* create controllers

## random notes
* zen coding -- emmet -> short hand plugin to generate html
* karma runner and jasmine test
* should always use objects for models, not primatives
* default goes into rootScope, get nested scopes via controllers
* can (popular trend now) to pull out items into their own modules (app, factories, directives, ...)
remove from global scope and prevents minification from screwing up special injected vars $<name>
```
myapp.controller("somename", [
	"$scope", "$resource,
	function($scope, $resource) { // by convention you keep the param name as above
		$scope.user = ...
	}
]);
```

## factory vs service
factories are singletons and returns a singleton object whenever invoked
service - invokes function with a new, it's constructor call, not a function call / this creates a singleton as well
### when to use:
factories - object of data to share across multiple controllers
services - rarely used. creating a user object from data coming over the wire..., need to have the constructor call

## use
* make an angular branch to dev in parallel 