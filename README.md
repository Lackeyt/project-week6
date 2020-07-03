#  _Currency Exchanger_

#### _Convert a user entered amount from one currency to another_
##### __Created:__ 7/3/2020
##### __Last Updated:__ 7/3/2020 
##### By _**Tyson Lackey**_  


## Description

_Using the exchangerate.com API, user inputted values are converted between available currencies. Users can select a "to currency" and a "from currency". The user entered amount is converted between the "from currency" and the "to currency." The original user entered amount and its currency code is displayed along with the converted value and the associated currency code of the new currency._

## Behaviors

| Spec| Example input | Example Output
| ----------- | ----------- | ----------- |
| If User enters a non-number return error | "seven" | "Please enter a number for currency amount" |
| If API Call succeds but returns an error result, return error | input | "The request returned an error:{API reponse error}' |
| If API Call fails, return error | input | "There has been an error processing your request" |
| User entered number is converted from one user selected currency to another | input | output |

## Setup/Installation Requirements

##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Open by downloading:
1. Internet Browser
2. Code editor like VScode to view the codebase

##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Open by downloading:

1. Download this repository onto your computer
2. Double click index.html to open it in your web browser

##### &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Open via Bash/GitBash:

1. Clone this repository onto your computer:
    "git clone https://github.com/Lackeyt/project-week6"
2. Navigate into the "project-week6" directory in Visual Studio Code or preferred text editor:
3. Open the project
    "code ."
4. Navigate to https://www.exchangerate-api.com/ in your web browser and follow the directions to receive your API key
5. create a .env file in the "project-week6" directory
6. in the .env file, enter "API_KEY = [your API key from step 4]"
4. Open your computer's terminal and navigate to the directory bearing the name of the program and containing the top level subdirectories and files.
5. Enter the command "$ npm install" in the terminal and press "Enter".
6. Enter the command "$ npm run build" in the terminal and press "Enter".
7. Enter the command "$ npm run start" in the terminal and press "Enter".


## Known Bugs

* n/a

## Support and contact details

* Discord: TysonL#4409
* Email: lackeyt90@gmail.com


## Technologies Used

* Visual Studio Code
* HTML
* CSS
* Bootstrap
* Javascript
* JQuery
* webpack

## Resources:

* https://sethrobertson.github.io/GitFixUm/fixup.html#bfg  -assistance with commit cleaning
* https://rtyley.github.io/bfg-repo-cleaner/  -tool used for commit cleaning
* https://www.exchangerate-api.com/  -API resource for exchange rates

### License

Copyright (c) 2020 **_Tyson Lackey_**

This software is licensed under the MIT license.