# Team-Generator

## Demo video 
https://drive.google.com/file/d/1yHrk_1l2qzGp2u1wsbukZH-X8T_h1cRO/view

### Installation 
To run this app, you will need to install package.json and make sure to have inquirer

### Description
This is a command line Team Profile generator.

It uses inquirer.prompt to ask the user questions related to their team members.
Only 1 manager is allowed with any number of Engineers and Interns, and the questions will loop through for the number of Engineers and Interns there are respectivly.

Using constructor classes for each team role, the data is then used to output an HTML document with the corresponding information.

This uses recursive functions, as I am not very skilled with promises. The asynchronization of the app contiunally messed up and caused things not to render, so to avoid that I nested the render functions and set up a recursive function, so as to not have both the questions for the Engineers and the Interns go off in the command line at the same time.

### Usage 
This app can be used for anyone wanting to keep track of their team members and their respective role, as well as a little bit of information about them.

### Contribution Guidelines
If you wish to contribute, I only ask that you leave the code better than when you found it.

### Tests
To test, type node run test in the command terminal.
