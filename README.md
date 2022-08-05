# LockedMe.com

Simple Java Console based program to allows user to input menu options for 

* Displaying File/Folder structure. 
* Search for File/Folder recursively.
* Add/Delete File/Folder recursively.

## View project locally

To try out the project in your local machine:

* clone this repository using `git clone `
* Open the folder from Eclipse/IntelliJ 
* Open LockedMeMain.java and Run


## Component Hierarchy

| File    |  Description           |
|-----------------|-------------------         |
| `LockedMeMain.java` | This class contains the Main method. It's the entry point of the program. |
| `MenuOptions.java` | This class contains methods for displaying menu options. |
| `HandleOptions.java` | This class contains methods for handling different options from user input and calls respective methods from FileOperations. |
| `FileOperations.java` | This class defines all the operations required for displaying, searching, deleting and adding files/folder.|



To track below deliverables - 

    Specification document - Product's capabilities, appearance, and user interactions

    Java concepts being used in the project 

    Data Structures where sorting and searching techniques are used. 

    Generic features and operations available: 

      1)  Retrieving the file names in an ascending order

      2)  Business-level operations:

            Option to add a user specified file to the application

            Option to delete a user specified file from the application

            Option to search a user specified file from the application

            Navigation option to close the current execution context and return to the main context

      3)  Option to close the application


Code to display the welcome screen. It shows:

* App name and developer details

* User interface details such as options to display user interaction information

* Function to accept user input to select one of the given options

* The first option returns the current filenames in ascending order. The root directory can be empty or contain several files or folders.

* The second option returns UI details such as options showing the following:

    * Add a file to an existing directory list

    * Remove user specified file from existing directory list

    * Find the file specified by the user from the main directory

    * Ability to go back to the main context

* There is a third option to close the application.

Implemented concepts such as exceptions, collections, and sorting techniques to optimize source code and increase performance
