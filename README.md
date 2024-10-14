# og-code-craft
# Code Craft Stock Trading Platform

## **Description**
This application is an easy to use stock trading software that automates the buying and selling of stocks - Amazon, Apple, Google, META, Microstoft, Tesla.  

## **Table of Contents**
1)  Tools

Software used to create, install, and use application
    
2)  How to Install and Run

Instructions for how to load the application on your device
    
3) How to Use

Instructions for how to implement the application
    
4)  How it works

A description of what happens behind the U
    
5) Credits

Computer Science Analysts


## **Tools**
- Visual Studio Code
- Alpaca

## **How to Install and Run**
- Download Visual Studio Code
- Download the zip file that includes each file  
- Open the folder in Visual Studio Code

- Go to https://app.alpaca.markets/account/login
  - Log in
  - click 'Home'
  - click 'Generate' or 'Regenerate' under API keys
  - copy Endpoint and Key
- Put your API key credentials from Alpaca into the config.py file

- pip intall Alpaca
- Run CombinedGrid.py

## **How to Use**
- Run the application in Visual Studio Code

To buy stocks:
- Click Activate button
  
To deactivate bot:
- Click Deactivae button

## **How it works**
- After the user clicks 'Activate Bot' on the welcome screen, this sends the command to the backend that purchases each stock. 
- The next screen called Selling Stocks shows a verifcation of what the users ordered.
  - This screen shows the total balance the user has, the time in force - day trading, and the price that each stock share was purchased at
- The next screen called Congrats shows the option for users to purchase another stock or not
    - if the user chooses to purchase another stock, clicking 'Yes', they will be taken back to the welcome screen, allowing them to restart the process
    - if the user chooses NOT to purchase another stock, clicking 'No', the program will quit

## **Credits**
Angela Darden

Darius Davenport

Winter Keemer

Casby Robinson

Jaden Smith

Fayed Troy
