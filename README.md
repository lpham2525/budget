# Unit 18 Performance Web Applications: Online/Offline Budget Trackers

Giving users a fast and easy way to track their money is important, but allowing them to access that information anytime is even more important. Having offline functionality is paramount to our applications success.

This assignment adds functionality to the existing Budget Tracker application to allow for offline access and functionality.

The user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they should populate the total when brought back online.

Offline Functionality:

  * Enter deposits offline

  * Enter expenses offline

When brought back online:

![Screenshot](./public/img/snapshot2.png?raw=true "Budget Tracker")

  * Offline entries should be added to tracker.

## User Story
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling

## Acceptance Criteria
GIVEN a user is on Budget App without an internet connection,
WHEN the user inputs a withdrawal or deposit,
THEN that transaction will be shown on the page and added to their transaction history when their connection is back online.
