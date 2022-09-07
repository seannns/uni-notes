Worldwide Web
	WWW = worldwide web
	Created by Tim berners Lee at CERN in 1989.
	"To link an access information of various kinds as a web of nodes in which the user can browse at will."
	HTTP: Protocol for accessing web.
	HTML: Language for describing web pages.
	URL: Method for identifying pages.

Advantages
	The web insulates clients and servers from one another. Any client can view a page, any server can view a page.
	Clients only need a web browser.
	Weblinks can be broken but this makes web infrastructure simple.
	Open standard - TCP/IP.

HTML
	Hyper text markup language
	Describes web pages

Getting web pages:
	1. Web page obtained using HTTP protocol layered on TCP/IP
	2. Browser issues HTTP GET request at a URL
	3. Receives response containing HTML data
	4. Web browser displays HTML data

Sending information to a web server
	Information can be uploaded to web server using a POST verb.

HTTP:
	Hyper text transfer protocol
	Communicates between browser and server.
	Operates over TCP/IP
	Contains several verbs: GET, POST, HEAD, OPTIONS, PUT, DELETE, TRACE, CONNECT
	HTTPS layers HTTP over SSL/TLS protocol for security.
	HTTP over TCP over IP. Web is JUST HTTP.

Status Codes
	200 = OK
	404 = Not Found
	500 = Internal Server Error
	503 = Service Unavailable

URL
	Universal Resource Locator
	Scheme = protocol (http://)
	Domain = DNS name (eg. www.qut.edu.au)
	Path = file path name on a server
	Query String = name value pairs
	URL can reference anything, not just web.

Javascript
	Programming language embedded in HTML
	Runs in browser, downloaded in web page.
	JIT compiled for efficiency.
	Allows interaction - eg. Google Docs

AJAX
	Asynchronous JavaScript and XML
	Web Apps
	Use asynchrous calls to server to get/send data through XML
	Now have the benefits of webapps
		No need to install apps
		Easy to update apps
		Platform independent
		Reduce client requirements - just need broser

Web Services
	Can use different client programs, not just JS in broswer. eg. native machine code
	Send data over HTTP rather than web page.
	Like a programming language library API
	Allows programs to be exposed as services across the web.
	eg. RPi project downloading and displaying weather from website, use it to animate display

State
	Many web apps use a state, eg. remembering a user or cart
	Can be represented in different ways
		Cookies - most reliable but can be turned off for security/privacy issues
		URL parameters