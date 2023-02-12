AirBnB clone

Description:
Web application

The Console:
The console is a command line interpreter that permits management of the backend of HolbertonBnB. It can be used to handle and manipulate all classes utilized by the application.

Using the console:
1. How to start it:
To use the HolbertonBnB console in interactive mode, run the file console.py by itself:

 $ ./console.py

2. how to use it:

The HolbertonBnB console can be run both interactively and non-interactively. To run the console in non-interactive mode, pipe any command(s) into an execution of the file console.py at the command line:

 $ echo "help" | ./console.py
 (hbnb) 
 Documented commands (type help <topic>):
 ========================================
 EOF  all  count  create  destroy  help  quit  show  update

 (hbnb) 
 $

While running in interactive mode, the console displays a prompt for input:
 $ ./console.py
 (hbnb) 

To quit the console, enter the command quit, or input an EOF signal (ctrl-D):
 $ ./console.py
 (hbnb) quit
 $

 $ ./console.py
 (hbnb) EOF
 $
