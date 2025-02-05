# Problem Statement

We have an account model with the following mandatory attributes (you can add atributes if needed):
* First Name
* Last Name
* ID

An Account can have multiple trades with the following mandatory attributes (you can add atributes if needed)
* AccountId
* SecurityCode (3 letters)
* Timestamp
* Amount
* Buy or Sell
* Status (Placed, Executed, Expired)

Create a 2-tier application in C# having a RESTFul API and a persistence layer.
* The CRUD API for Accounts
* The Search API for Accounts by its attributes such as ID or Last Name which should be efficient and prevent known exploits.
* The API for trades
    * Place Trade
    * Update Trade (change its status)
* The persistence layer can use a data store of your choice (example: PostgreSQL on Docker, SQLite, or just files on disk). 

## What we will be looking at
* OOP & Solid Principles
* Input validation.
* Efficent Data structures (if any).
* Design patterns.
* Unit testing.
* README.md on how to run your solution.
* Bonus for caching of the Least Recently Using accounts so that the application can scale.


