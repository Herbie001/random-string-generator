# random-string-generator web application markdown file.

## Motivation
The motivation behind this project was my fascination with generating random strings. Additionally,
generating long random passwords is becoming essential to protect your information online.

## Program Objective 
Generate four different types of random strings based on desired length, put them into a database, and give
the user the ability to download as a text file if they wish. 

## How to compile and run the program
While in the RandomStringDirectory, run 'node server.js', then go to the url specified.
After reaching the web application, select one of the four tabs and enter a desired length.


## Back End Implementation 

Below are the essential function with description and time complexities.

| **Methods**     | **Description** | **Time Complexity** |
|:---------------:|:---------------:|:-------------------:|
| overFlow        | Function to determine if the input will cause and overflow error | O(1), boolean check |
| uniqueStringGen | Function to generate a unique ASCII string of [0,94] characters long | O(1) |
| asciiStringGen  | Function to generate a non-unique ASCII character string | O(L), the length of the desired word |
| alphaNumerical  | Function to generate a random string consisting strictly of alphanumerical characters | |O(L), the length of the desired word |
| randomWordGen   | Function to generate a random string consisting strictly of alphabetical character | O(L), the length of the desired word |


## Front End Implementation

Below are the essential functions with descriptions and time complexities.

| **Methods** | **Description** | **Time Complexity** |
|:-----------:|:---------------:|:-------------------:|
| overFlow        | 
| uniqueStringGen |
| asciiStringGen  |
| alphaNumerical  |
| randomWordGen   |



## Examples
Please take a look at the "stored_strings.txt" file located in the RandomStringDirectory to see examples.