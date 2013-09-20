yoWebSvc
========

Yeoman generator to create a node web service based on restify with a few added features.

It will create a diectory structure that will aid multi-discipline development. 
Directories will exist for build/deployment, testing, and documentation to allow easy ramp up for
anyone coming on to the project. 

Plans are to have the generator read the mongo database(s) and allow the capability to create mongoose 
based models as well as CRUD controller methods for the collections. 

Also routes will be provided for Admin that will aid in checking as far as status of the system.

Also configuration will be as much as possible pushed to declaritive JSON files. 

The combinaton of the past two features should make it easier to make changes to or manage
the system without overly involving developer actions and also leaves us with the possibility of 
providing pages that can adjust the system in a disconnected and dynamic manner.

