# random-string-generator web application

## Motivation
The motivation behind this project was my fascination with generating randomness 
which was then directed at numbers, characters and then concatenating those 
characters into strings. Additionally, generating long randomly generated 
strings is becoming essential in todays world to protect vital 
information stored online.

## Program Objective 
Generate four different types of random strings based on desired length utilizing 
the mersenne twister and a uniform distribution of integers representing ASCII 
characters. Store the strings into a database which the user can easily download 
as a .txt file. If the user would like, they may also clear the database to 
generate different strings. 

## How to compile and run the program
You are able to download, fork or clone the repository on your own machine. 
Afterwards, make your way to the directory on your machine, start up your IDE.
While in the random-string-generator directory, run 'node server.js' in terminal, 
then go to the url specified. After reaching the web application, select 
one of the four tabs, enter a desired length, and click generate.


## Back End Implementation 

Below are the essential function with description and time complexities.

| **Methods**     | **Description** | **Time Complexity** |
|:---------------:|:---------------:|:-------------------:|
| overFlow        | Function to determine if the input will cause and overflow error | O(1), boolean check |
| uniqueStringGen | Function to generate a unique ASCII string of [0,94] characters long | O(1), the length of the desired word |
| asciiStringGen  | Function to generate a non-unique ASCII character string | O(L), the length of the desired word |
| alphaNumerical  | Function to generate a random string consisting strictly of alphanumerical characters | O(L), the length of the desired word |
| randomWordGen   | Function to generate a random string consisting strictly of alphabetical character | O(L), the length of the desired word |


## Examples
Please look [here](https://github.com/Herbie001/random-string-generator/tree/main/examples) 
to see examples of the out put file from generating two strings of length 20 from 
each of the four options available.