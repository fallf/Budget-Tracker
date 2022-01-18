# Budget Tracker

## Description

This application allows users to track their money even while offline. When transactions are made offline, the totals are updated when brought back online.

## Table of Contents

- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Technology Used](#technology-used)
- [Questions](#questions)

## User Story

```
AS AN avid traveler
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling
```

## Acceptance Criteria

```
GIVEN a budget tracker without an internet connection
WHEN the user inputs an expense or deposit
THEN they will receive a notification that they have added an expense or deposit
WHEN the user reestablishes an internet connection
THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated
```

## Installation

To install this application, clone the code into your terminal for the respective repository. Then, install npm by entering the command `npm install` into the terminal. This will install all dependencies in the `package.json` required to run this application.

## Usage

Run the following commands in the command-line in the root of the folder

1. npm install
2. npm start
3. Run the browser: http://localhost:3002/
4. In the "Name of transaction" field, enter the name of the transaction
5. In the "Transaction amount" field, enter the transaction amount
6. Click either "Add Funds" or "Subtract Funds" based on whether you would like to add or subtract those funds to your budget
7. Continue to add and subtract funds as you make transactions

## License

This application is rendered under MIT

## Technology Used

• Javascript
• Bootstrap
• Node
• HTML
• CSS
• mongoose
• express
• manifest
• morgan
• compression

## websites

Github: https://github.com/fallf/Budget-Tracker
website:https://polar-shore-33334.herokuapp.com/
