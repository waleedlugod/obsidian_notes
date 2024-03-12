# What
web server: can be hardware or software
handling HTTP requests
retrieving/returning data from databases

## Static site server
browser -> HTTP request -> web server -> HTTP Response -> Browser

## Dynamic site server
Browser -> HTTP GET -> web server (request data) -> web application (retrieve data & populate HTML) -> web server -> files -> HTTP Response -> Browser

## Server-side programming
environment is controlled
web frameworks:
* provide constructs
* store  & deliver information
* customized experiences
* use access control
* session/state
* notification & communication

# How
## HTTP and web servers
web clients and server connect via HTTP (HyperText Transfer Protocol)
HTTP:
* URL
* HTTP method
* additional parameters, POST data, cookies

### URL
protocol://domain.tld/foo
tld: top level domain
protocols: https, http, ftp, etc

### HTTP
Methods:
GET: get resource
POST: create resource
HEAD: get metadata
PUT: update/create resource
PATCH: partially update resource
DELETE: delete resource

Parameters:
URL params: for get request; after ?; insecure
POST data
cookies

## Web frameworks
meidation between client and server via HTTP
look for data (HTML, JSON, CSV)

handled by framework:
* work with HTTP requests/responses
* routing to appropriate handler
* abstract database

## MVC
model view control
separation of concern