# Todoapp-list-python

### Project Details
[Python Flask](http://flask.pocoo.org) Webpage for a Todoapp list with [AWS RDS/MYSQL Backend](https://aws.amazon.com/rds/mysql/). Using [SQLAlchemy](http://flask-sqlalchemy.pocoo.org/) for database connection as well as object mapping. Flask will be used for the server and displaying. [Flast-RESTPlus](http://flask-restplus.readthedocs.io/en/stable/) will be used for anyone trying to call via API's. Pages are in HTML with CSS styling. Inserting Todoapps with date is done with natural language via [Recurrent](https://github.com/kvh/recurrent).

Going to be used for personal use. Here are [SQL files](https://github.com/shauravkhadka/Todoapp/tree/master/Resources) to create DB as well as fake copy of properties ([properties_test.ini](https://raw.githubusercontent.com/shauravkhadka/Todoapp/master/properties_test.ini)) to show how it is used and implemented.
***
### How to use API
[Flast-RESTPlus](http://flask-restplus.readthedocs.io/en/stable/) was used to build a REST server so that the list and other information is accessible from API's.

In your chosen API client (curl via terminal, [Postman](https://www.getpostman.com), etc) do a GET request for `<base_url>/Todoapp_api/<your_api_key>`. You must add an api_key to your user in the database. Full list of API available at a later time 

***
### Screenshot
![alt text](https://raw.githubusercontent.com/shauravkhadka/Todoapp/master/images/Screenshots/home_screenshot_1.2.png "Screenshot of Homepage")

![alt text](https://raw.githubusercontent.com/shauravkhadka/Todoapp/master/images/Screenshots/restore_screenshot_1.0.png "Screenshot of Restore / Deleted")

***

### UML Diagrams
Overall view of the schema design. Using [StarUML](http://staruml.io) for diagramming.
## 1.5
![alt text](https://raw.githubusercontent.com/shauravkhadka/Todoapp/master/images/UMLs/Todoapp-UML-1.5.png "Version 1.5 UML")
### Older versions
* [1.4 - no api_key](https://raw.githubusercontent.com/shauravkhadka/Todoapp/master/images/UMLs/Todoapp-UML-1.4.png) 
* [1.3 - No completed/not completed](https://raw.githubusercontent.com/shauravkhadka/Todoapp/master/images/UMLs/Todoapp-UML-1.3.png) 
* [1.2 - Before user_log_activity](https://raw.githubusercontent.com/shauravkhadka/Todoapp/master/images/UMLs/Todoapp-UML-1.2.png) 
* [1.1 - Did not have password attributes](https://raw.githubusercontent.com/shauravkhadka/Todoapp/master/images/UMLs/Todoapp-UML-1.1.png) 
* [1.0 - Wrong order on cardinality](https://raw.githubusercontent.com/shauravkhadka/Todoapp/master/images/UMLs/Todoapp-UML-1.0.png) 

*** 


