#Welcome to AirBnB clone project
AirBnB clone project is the first step towards building a first full web application. This first step consists of a custom command-line interface for data management, and the base classes for the storage of this data.

Step 1: Write a command interpreter to manage AirBnB objects
This is the first step towards building your first full web application: the AirBnB clone. This first step is very important because you will use what you build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration…

Each task is linked and will help you to:

put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances

create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file

create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel

create the first abstracted storage engine of the project: File storage.

create all unittests to validate all our classes and storage engine

What’s a command interpreter?
Create a new object (ex: a new User or a new Place)

Retrieve an object from a file, a database etc…

Do operations on objects (count, compute stats, etc…)

Update attributes of an object

Destroy an object

Resources
cmd module
uuid module
datetime
unittest module
args/kwargs
Python test cheatsheet

Authors
Chibuwze Okorie - izy4eze
Akanji Ayomide - Ayomidegideon122
