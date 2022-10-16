### Conceptual Exercise

Answer the following questions below:

- What are important differences between Python and JavaScript?
### Python is a high-level general-purpose programming language that was developed to emphasis code readability. JavaScript is a programming language that conforms to the ECMAScript specification. It is a scripting language used for developing both desktop and web applications. It is a client side scripting language.

- Given a dictionary like ``{"a": 1, "b": 2}``: , list two ways you
  can try to get a missing key (like "c") *without* your programming
  crashing.
### Using get(key,def_val)
### Using setdefault(key, def_value) 

- What is a unit test?
### A unit test is a way of testing a unit - the smallest piece of code that can be logically isolated in a system. In most programming languages, that is a function, a subroutine, a method or property. T

- What is an integration test?
### Integration testing exercises two or more parts of an application at once, including the interactions between the parts, to determine if they function as intended. This type of testing identifies defects in the interfaces between disparate parts of a codebase as they invoke each other and pass data between themselves.

- What is the role of web application framework, like Flask?
### A web framework (WF) or web application framework (WAF) is a software framework that is designed to support the development of web applications including web services, web resources, and web APIs. Web frameworks provide a standard way to build and deploy web applications on the World Wide Web.

- You can pass information to Flask either as a parameter in a route URL
  (like '/foods/pretzel') or using a URL query param (like
  'foods?type=pretzel'). How might you choose which one is a better fit
  for an application?
### If it is a search field, use URL query param. If if is a determined field, use route URL. 


- How do you collect data from a URL placeholder parameter using Flask?
### use request.args.get() to get parameters from URL

- How do you collect data from the query string using Flask?
### request.args.get('param')

- How do you collect data from the body of the request using Flask?
### request.form

- What is a cookie and what kinds of things are they commonly used for?
### Cookies are text files with small pieces of data — like a username and password — that are used to identify your computer as you use a computer network. Specific cookies known as HTTP cookies are used to identify specific users and improve your web browsing experience.

- What is the session object in Flask?
### In the flask, a session object is used to track the session data which is a dictionary object that contains a key-value pair of the session variables and their associated values. 

- What does Flask's `jsonify()` do?
### jsonify serializes data to JavaScript Object Notation (JSON) format, wraps it in a Response object with the application/json mimetype. 