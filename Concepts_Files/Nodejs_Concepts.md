Lets Start with Node:

Node Js: 
	1) JavaScript runtime: Nodejs is an open source cross platform runtime enviornment for JS to run outside browser.
	2) Nodejs is an JS in a different enviornment, means running JS on different servers or any machine.
	3) Built on chromes V8 Engine: It run's on the V8 engine which compile JS directly complies the JS to the native machine code enhancing the performance.
	4) V8 is written in C++ for speed.
	5) V8 + Backend features = NodeJS
	
	Design: Features an Event-driven, non-blocking I/O model for efficiency.
	Full-stack JS: Allows using JS on both server and client side.
	Scalability: Ideal for scalable network application due to its architecture.
	versatality: suitable for web, real-time chats, and REST API servers.
	
NodeJS Features: 
		Multiple clients request -> event loop(single thread non-blocking -> create worker threads (delagate long timing jobs) -> callback resposne
	1) Non-blocking I/O: Designed to perform non-blocking operations by default, making it suitable for I/O hevay operation.
	2) Networking Support: Supports TCP/UDP sockets, which are crucial for building lower-level network applications that browser can't handle.
	3) File system access: Provides API's to read/write files directly which is not possible to browser enviornements for security reasons.
	4) Server-side capabilities: Nodejs enables the JS to run on the server, handling HTTP requests, file operations, other server-side functionality.
	5) Modules: organized code into reusable modules using require() keyword.
--------------------------------------------------------------------------------------------------------------------------------------------------
	
JS on Client: 
	Html/CSS/JS -> chrome -> rendering -> webPage
	
JS on Server: 
	1) Database management: Stores, retrives and manages data efficiently through operations like CURD etc.
	2) Authentication: Verifies user identity to control access to the system, ensuring that the user are who they claim to be.
	3) Authorization: Determines what authenticated user are allowwed to do by managing permissions and access control.
	4) Input validation: Checks incoming data for correctness, completness and security to prevent malicious data entry and errors
	5) Session Management: Tracks user activity accorss varios requests to maintain state and manage user specific settings.
	6) APi Management: Provides and handles interfaces for application to interact, ensuring the smooth data excange and integration.
	7) Error-handling: manages and respoond to the errors effectively to maintain system stability and provide usefull error messages.
	8) Security Measures: Implements protocols to protect data from unauthorised access and attacks such as SQl injection and cross-site scripting (XSS).
	9) Data Encryption: Secures sencitive information by encrypting data stored in DB and during transmission.
	10) Logging and monitoring: keeps records of system activity to diagnoose issues and monitor system health and security.
	etc
	
Real time Applications: Effeciently manages real-time data applications such as chat apps and live updates using web-socket.
------------------------------------------------------------------------------------------------------------------------------------------------
Server architecture with Nodejs: 
	Nodejs server will:	
		1) Create server and listen to incomming request.
		2) Business logic: Validation, Connect to DB, actual processing of data.
		3) Returns resposne HTML, JSON, CSS, JS.
-------------------------------------------------------------------------------------
		
REPL: READ, EVAL, PRINT, LOOP:
	1) Read user input
	2) Evaluate user input
	3) Print output (Result)
	4) Loop input 
	
-----------------------------------------------------------------------------------

First Node Server: 

	DNS: (Domain Name Service)
		1) Domain name entry: user types domain name (www.google.com) in browser.
		2) DNS Query: The browser send the dns query to resolve the domain into and IP address.
		3) DNS server: Provide correct IP address for the domain.
		4) Browser connections: The browser uses the IP to connect to the web-server and loads the website.
		
	How web works: 
		1) Client requests initiation.
		2) DNS resolution: The browser send the dns query to resolve the domain into and IP address of domain.
		3) TCP connection: Browser establish the TCP connection with the server address.
		4) HTTP request: browser sends http requests to server.
		5) server processing:
		6) http resposne:
		7) network transmission:
		8)client recives resposne:
		9)Rendering.
		
	Protocols:
		1) HTTP (Hypertext transafer protocaol):
			a) Faciliatets the communitaion between a web-browser and the server to transfer web pages.
			b) Sends data in plain text.
			c) Used for basic websites without security.
				
		2) HTTPS ( Hypertext transfer protocol secure):
			a)Secure version of HTTP, encrypts data for secure communication.
			b)Uses SSL/TLS to encrypt data.
			c)Used in ecommers/online banking.
			
		3) TCP (Transmission control protocol);
			a) Ensures reliable, ordered and error-checked data deleviery over the internet.
			b) Establishes a connection before data is transfered.
			
----------------------------------------------------------------------------------------------------
			
Node js Core modules: 
	1) fs (file system): File operations like read/write files.
	2) http: creates http server and makes http request

		