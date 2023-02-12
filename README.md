# Airbnb Console

## Description
The Airbnb Console project is a command line interface program that allows users to create, update, show and delete objects stored in a file storage system. This project was created to demonstrate the use of classes and inheritance in Python, as well as file storage and serialization/deserialization.

## Image of Airbnb Console
(add image here)

## Command Interpreter
The command interpreter is the main component of the Airbnb Console project. It is responsible for receiving user input, parsing the input to determine the desired action, and executing that action by calling the appropriate method from the object classes.

## Starting the Command Interpreter
To start the command interpreter, run the console.py file in a terminal or command prompt.

## Using the Command Interpreter
The command interpreter provides the following commands:

- `create`: creates a new object of the specified type (e.g. `create BaseModel`)
- `show`: shows the string representation of an object (e.g. `show BaseModel 1234-1234-1234`)
- `all`: shows all objects, or all objects of a specified type (e.g. `all BaseModel`)
- `update`: updates an object's attributes (e.g. `update BaseModel 1234-1234-1234 email "new_email@example.com"`)
- `destroy`: deletes an object (e.g. `destroy BaseModel 1234-1234-1234`)
- `quit`: quits the program

## Examples
### Creating a new BaseModel object:

```python
(hbnb) create BaseModel
6d1d6c2f-bc6b-4f1e-8f05-e5b5d5b94c3c`
```
### Showing am object

'(hbnb) show BaseModel 6d1d6c2f-bc6b-4f1e-8f05-e5b5d5b94c3c
[BaseModel] (6d1d6c2f-bc6b-4f1e-8f05-e5b5d5b94c3c) {'created_at': datetime.datetime(2022, 2, 11, 2, 17, 59, 713277), 'id': '6d1d6c2f-bc6b-4f1e-8f05-e5b5d5b94c3c', 'updated_at': datetime.datetime(2022, 2, 11, 2, 17, 59, 713298)}'

### Updating an object's attributes:

'(hbnb) update BaseModel 6d1d6c2f-bc6b-4f1e-8f05-e5b5d5b94c3c first_name "John"
(hbnb) show BaseModel 6d1d6c2f-bc6b-4f1e-8f05-e5b5d5b94c3c
[BaseModel] (6d1d6c2f-bc6b-4f1e-8f05-e5b5d5b94c3c) {'created_at': datetime.datetime(2022, 2, 11, 2, 17, 59, 713277), 'id': '6d1d6c2f-bc6b-4f1e-8f05-e5b5'
