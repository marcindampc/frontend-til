# API - Application Programming Interface
* shares minimum data with outer systems
* usually well documented
* create with integration in mind
* upgrades security
WebAPI
* uses HTTP
* usually JSON XML
* often for promotion of some Websites
* sometimes Web API becomes business

# SOAP - Simple Object Access Protocol
* needs XML
* data as service (verb)
  i.e
  * Salesforce SOAP API
  * Paypal SOAP API
  * Clickatell SMS SOAP API

# REST - REsources State Transfer
* open-source
* could be JSON / PO-XML / RSS/ATOM
* data as resource (noun)
  i.e.
  * Twitter API
  * Linkedin API
  * Slack API
  * mobile services
  
## REST verbs
* POST
* GET
* PUT
* PATCH
* DELETE

## REST constrains
* client - server (request - response)
* stateless
* cacheable
* Uniform Interface
* Layered System (connection with top layer only)

# JSON - JavaScript Object Notation
* object
{
  name: 'Myname',
  age: 123
}

* array
[
{"name": "Myname", "age": "123"},
{"name": "Hername", "age": "12"}
{"name": "Hisname", "age": "1"}
]
* value 
* string
* number

example jQuery AJAX
```
$.ajax({
url: "endpoint/url",
method: "GET",
data: {"param":"value"},
dataType: "json",
success: function(result){ }
});
```

example JavaScript Fetch
```
fetch('endpoint/url', {
method: 'post',
headers: {
'Content-Type': 'application/json'
},
body: JSON.stringify({ param: value })
}).then(function(response) { });
```
