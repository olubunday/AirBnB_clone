This project is the first part of the AirBnB clone. In this part, we work on the back-end project whiles interfacing it with a console application with the help of the cmd module in python.
Data (python objects) generated are stored in a json file and can be accessed with the help of the json module in python.

Description of the command interpreter:
The interface of the application is just like the Bash shell except that this has a limited number of accepted commands that were solely defined for the purposes of the usage of the AirBnB website.

This command line interpreter serves as the frontend of the web app where users can interact with the backend which was developed with python OOP programming.

Some of the commands available are:

show
create
update
destroy
count
And as part of the implementation of the command line interpreter coupled with the backend and file storage system, the folowing actions can be performed:

Creating new objects (ex: a new User or a new Place)
Retrieving an object from a file, a database etc…
Doing operations on objects (count, compute stats, etc…)
Updating attributes of an object
Destroying an object.

FILES IN THIS PROJECT
In here there will be several files that allow the program to work.

/console.py : The main executable of the project, the command interpreter.

models/engine/file_storage.py: Class that serializes instances to a JSON file and deserializes JSON file to instances

models/__ init __.py: A unique FileStorage instance for the application

models/base_model.py: Class that defines all common attributes/methods for other classes.

models/user.py: User class that inherits from BaseModel

models/state.py: State class that inherits from BaseModel

models/city.py: City class that inherits from BaseModel

models/amenity.py: Amenity class that inherits from BaseModel

models/place.py: Place class that inherits from BaseModel

models/review.py: Review class that inherits from BaseModel

AUTHORS
Akinlowo Olumide Adeola <adeolaolumide@gmail.com>
Adesola Deborah <debbyrinsola@gmail.com>
