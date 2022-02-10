# **AirBnB_clone project**

## Description
HolbertonBnB is a complete web application, integrating database storage, a back-end API, and front-end interfacing in a clone of AirBnB.

The project currently only implements the back-end console.
## *Classes*

# *storage*
The above classes are handled by the abstracted storage engine defined in the FileStorage class.

Every time the backend is initialized, HolbertonBnB instantiates an instance of FileStorage called storage. The storage object is loaded/re-loaded from any class instances stored in the JSON file file.json. As class instances are created, updated, or deleted, the storage object is used to register corresponding changes in the file.json.

# *Console*
The console is a command line interpreter that permits management of the backend of HolbertonBnB. It can be used to handle and manipulate all classes utilized by the application (achieved by calls on the storage object defined above).

## *using the console*
The HolbertonBnB console can be run both interactively and non-interactively. To run the console in non-interactive mode, pipe any command(s) into an execution of the file console.py at the command line.

<h1 Authors h1>
    <p Ruth Mensire p>
    <p Olani Baissa p>

