# PWA Online/Offline Budget Trackers

Add functionality to our existing Budget Tracker application to allow for offline access and functionality.

The user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they should populate the total when brought back online.

Offline Functionality:

  * Enter deposits offline

  * Enter expenses offline

When brought back online:

  * Offline entries should be added to tracker.

## User Story
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling

## Business Context

Giving users a fast and easy way to track their money is important, but allowing them to access that information anytime is even more important. Having offline functionality is paramount to our applications success.


## Acceptance Criteria
GIVEN a user is on Budget App without an internet connection
WHEN the user inputs a withdrawal or deposit
THEN that will be shown on the page, and added to their transaction history when their connection is back online.


## Links

Repository:
https://github.com/dasloinc/PWA-Buget-Tracker

Heroku:
https://pwa-budget-trackers.herokuapp.com/

### Using the Application:
In your terminal run the following commands one at a time:

git clone https://github.com/dasloinc/PWA-Buget-Tracker

cd PWA-budget_Tacker

- npm install
- express
- logger
- compression
- mongoose

Once the steps are completed and the npm packages have been installed continue with:

node server.js Now continue with terminal to check how the application saves while online/offline.
