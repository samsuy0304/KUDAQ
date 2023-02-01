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
 A rule can be thought of as page. In <pre> http://127.0.0.1:5000/hello </pre>, the rule <pre> '/hello' </pre> is bound to the function <pre> hello_world() </pre>.
 
 A rule can either be added using <pre> route() </pre> or <pre> app.add_url_rule(rule, function) </pre>.
