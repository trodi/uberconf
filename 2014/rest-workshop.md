# rest workshop
initial web -- information sharing when you can't standardize platforms --> cern

* URI - identity of resource, does not tie to representation
* representation - resource abstraction
* resource - 

org needs to imbrace the web internally (not a centrally planned economy)

* web has a very successful naming sys vs other systems
	* first/last name - many collisions
	* database keys - tied to context
	* SS number - sensitive info
* name of a thing is the way in which we interact with it
* only thing that makes a good url good is that it is stable -- wont change due to impl etc.
* avoid putting version in your API in the identity/name
* "A cool URI is one that does not change." (article)
* avoid
	* author name
	* status
	* org structure
	* file name ext
	* software mechanism (branded to .php or node ... leaks impl details)
* don't reflect plurality in URI (/person, not /persons)
* http://example.com/account/id/1234
* http://example.com/account/status/gold
* left most element defines what you will get back (return a set of accounts)

exersize: design info space for something... (fast food restaurant)
* first level is identity
* second level is http
* third level is hypermedia
### verbs
* GET - let clients cache, also idempotent so they can re-try without side affects
	* IDEMPONTENT
* PUT - allow clients to name the provided resource, an overwrite action if already exists
	* IDEMPONTENT
* POST - gives server to figure out identity and process and return any identity client needs
	* used when client doesn't know what to call something
	* or partial update
	* mutates state
	* NOT IDEMPONTENT
* DELETE - 
	* IDEMPONTENT -  re deleting should give the same response
* HEAD - don't send me, just tell me about it - meta-data
* OPTIONS - what can I do
* PATCH - partial update verb, allows for idempotent update (instead of POST)
### response codes
* provides uniform conversation

putting file extensions forks the identity -- instead let the accept header request the format

## part 2
* apiary.io
* http://developers.meethue.com/
exercise - roles, verbs on resources

### hypermedia
tell the client what to do and how to do it versus having to publish an API doc that you have to read
* example of media type: collections + json

### security
ahhhhhhh
* principle of least privilege
* fortify static code analysis
* CORS - preferred
* JSONP
	* works with older browsers
	* only with GET
* look at slides for the rest ...