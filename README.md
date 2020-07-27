# Unit 18 Performance Web Applications: Online/Offline Budget Trackers

Giving users a fast and easy way to track their money is important, but allowing them to access that information any time is even more important. Having offline functionality is paramount to our application's success. Enter the Budget Tracker, an application which allows the user to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they should populate the total when brought back online.

Link to live app: https://guarded-spire-68532.herokuapp.com/

Offline Functionality:
-------------------------------------------------------------

  * Enter deposits offline: type in the name and amount of the deposit, then click on "Add Funds" button.

  * Enter expenses offline: type in the name and amount of expenses, then click on "Subtract Funds" button.

When brought back online:
-------------------------------------------------------------------

![Screenshot](./public/img/snapshot.png?raw=true "Budget Tracker")

  * Offline entries should be added to tracker.

## User Story
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling

## Acceptance Criteria
GIVEN a user is on Budget App without an internet connection,
WHEN the user inputs a withdrawal or deposit,
THEN that transaction will be shown on the page and added to their transaction history when their connection is back online.

Technologies Used
---------------------------------------------------
JavaScript, Node, Express, Compression, Mongoose, MongoDB