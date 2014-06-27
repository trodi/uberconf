# angular session
* came into google as part of an acquisition
* all new projects at google will angular
* can make just a specific element an angular app (so instead of the body, could have just a div)
* auto two way binding
* build for testing
* provides dependency injection
* always start with the view and work your way back
* mixing with jquery plugins
	* if plugin manipulates the DOM, either it needs to be separate from angular modles or you need to wire them together via a directive

## cool features
* $timeout
* ng-idle
* <li ng-repeat ng-model="t in todos | filter:searchText | orderBy:'-done'"> ... </li>
	* https://docs.angularjs.org/api/ng/filter/filter