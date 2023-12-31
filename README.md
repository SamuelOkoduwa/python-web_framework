Python - Web framework

Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

General
What is a Web Framework
How to build a web framework with Flask
How to define routes in Flask
What is a route
How to handle variables in a route
What is a template
How to create a HTML response in Flask by using a template
How to create a dynamic template (loops, conditions…)
How to display in HTML data from a MySQL database

Tasks
0. Hello Flask!
Write a script that starts a Flask web application:
-	Your web application must be listening on 0.0.0.0, port 5000
-	Routes:
	-	/: display “Hello HBNB!”
-	You must use the option strict_slashes=False in your route definition

1. HBNB
Copy the previous task to a new script that starts a Flask web application:
-	Your web application must be listening on 0.0.0.0, port 5000
-	Routes:
	-	/: display “Hello HBNB!”
	-	/hbnb: display “HBNB”
-	You must use the option strict_slashes=False in your route definition


2. C is fun!
Copy the previous task to a new script that starts a Flask web application:
-	Your web application must be listening on 0.0.0.0, port 5000
-	Routes:
	-	/: display “Hello HBNB!”
	-	/hbnb: display “HBNB”
	-	/c/<text>: display “C ” followed by the value of the text variable (replace underscore _ symbols with a space )
-	You must use the option strict_slashes=False in your route definition


3. Python is cool!
Copy the previous task to a new script that starts a Flask web application:
-	Your web application must be listening on 0.0.0.0, port 5000
-	Routes:
	-	/: display “Hello HBNB!”
	-	/hbnb: display “HBNB”
	-	/c/<text>: display “C ”, followed by the value of the text variable (replace underscore _ symbols with a space )
	-	/python/<text>: display “Python ”, followed by the value of the text variable (replace underscore _ symbols with a space )
		-	The default value of text is “is cool”
-	You must use the option strict_slashes=False in your route definition

4. Is it a number?
Copy the previous task to a new script that starts a Flask web application:
-	Your web application must be listening on 0.0.0.0, port 5000
-	Routes:
	-	/: display “Hello HBNB!”
	-	/hbnb: display “HBNB”
	-	/c/<text>: display “C ”, followed by the value of the text variable (replace underscore _ symbols with a space )
	-	/python/<text>: display “Python ”, followed by the value of the text variable (replace underscore _ symbols with a space )
	-	The default value of text is “is cool”
-	/number/<n>: display “n is a number” only if n is an integer
-	You must use the option strict_slashes=False in your route definition

5. Number template
Copy the previous task to a new script that starts a Flask web application:
-	Your web application must be listening on 0.0.0.0, port 5000
-	Routes:
	-	/: display “Hello HBNB!”
	-	/hbnb: display “HBNB”
	-	/c/<text>: display “C ”, followed by the value of the text variable (replace underscore _ symbols with a space )
	-	/python/<text>: display “Python ”, followed by the value of the text variable (replace underscore _ symbols with a space )
		-	The default value of text is “is cool”
	-	/number/<n>: display “n is a number” only if n is an integer
	-	/number_template/<n>: display a HTML page only if n is an integer:
		-	H1 tag: “Number: n” inside the tag BODY
-	You must use the option strict_slashes=False in your route definition