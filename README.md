# Budget Tracker

https://infinite-escarpment-00072.herokuapp.com/

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

## Deployed Site

![Website](./assets/screenshot.png)

## Description

This website allows users to track their spending, and has the ability to be accessed as a PWA and while offline. Users input income and expenditures. It utilizes services workers and indexDB to provide user access offline.

## Built With
- HTML
- CSS
- JavaScript
- MongoDB
- MongoDB Atlas
- Heroku

## Licesne

This is liscensed under ISC