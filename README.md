# random-string-generator web application

## Motivation
The motivation behind this project was my fascination with generating randomness which
was then directed at numbers, characters and then concatenating those characters into strings. 
Additionally, generating long randomly generated strings is becoming essential in todays 
world to protect vital information stored online.

## Program Objective 
Generate four different types of random strings based on desired length, put them into a database, and give
the user the ability to download as a text file if they wish. 

## How to compile and run the program
You are able to download, fork or clone the repository on your own machine. Afterwards,
make your way to the directory on your machine, start up your IDE.
While in the RandomStringDirectory, run 'node server.js' in terminal, then go to the url specified.
After reaching the web application, select one of the four tabs and enter a desired length.
Each string you generate will be stored in a database which you are able to download if you wish.
If you would like to clear the database to generate more, you are able to do that as well.


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