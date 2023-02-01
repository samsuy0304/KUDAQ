# Working with Flask

## Importing Flask library
 <pre> from flask import Flask </pre>
 Importing the module is mandatory. 

 The Flask constructor will take the name of current module as argument.
 <pre> app = Flask(__name__) </pre>
 
## Routing
A URl consists of host, port, and rule.
 #### Host
 Hostname to listen on. Defaults to 127.0.0.1 (localhost). Set to ‘0.0.0.0’ to have server available externally
 #### Port 
 Defaults to 5000
 #### Rule
 A rule can be thought of as page. In `http://127.0.0.1:5000/hello`, the rule `'/hello'` is bound to the function ` hello_world()`.
 
 A rule can either be added using ` route()` or ` app.add_url_rule(rule, function) `.
