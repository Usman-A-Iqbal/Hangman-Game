# Hangman-Game
A text-based Hangman game developed using object-oriented Java. 


# Object Orientated Analysis and Design
Encapsulation and information hiding – each class has its own attributes and methods. Some of these attributes and methods may have a private modifier. 
Inheritance – extending the Exception class to create a user defined exception for the Hangman game.
Polymorphism – overriding the “toString” method provided by the Exception class
Arrays – used to hold the pool of potential words,  the hangman and used to print the board. 


# UML class diagram

Input exception class extend Exception (a built-in java class).
Player class calls upon the user defined exception when user input is not within the valid range.
The Game class contains a player attribute.
The Main method then calls the play game function


![image](https://github.com/user-attachments/assets/7cbc742d-fab8-43f0-becb-f498a8673cc5)
