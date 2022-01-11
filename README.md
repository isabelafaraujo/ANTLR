## Introduction to ANTLR
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
This repository is an introduction to the ANTLR, ANother Tool for Language Recognition. Initially some simple examples were made to get familiar with the Parser generator and with the progress some other examples will be updated, as well as new projects involving the language. 

## Technologies
Project is created with:
* ANTLR version: 4
	
## Setup
To run this project I used the IntelliJ IDE with the ANTLR plugin and suport. To generate a grammar using ANTLR it is important that the filename is the same as the name of the grammar and that the file is in the .g4 extension, for example: 

```
grammar Hello;

r   : 'hello' ID;
ID  : [a-z]+ ;
WS  : [ \t\r\n]+ -> skip
``` 

And this file needs to be saved as Hello.g4
 
