![cf](https://i.imgur.com/7v5ASc8.png) 
# 401 JS --  Lab 42 - SQL vs NoSQL Research

## Submission Instructions
  * You may choose to work by yourself or with a partner
  * Select any lab or project you've worked on in this class, and make a new branch called `lab-42`
  * Make a PR from that branch to your selected repo's master
  * Submit on Canvas the following:
    * A link to your PR
    * How long you spent on this lab
    * At least four sentences concluding if you prefer to use SQL or MongoDB in the upcoming project

 
## Feature Tasks 
* Select any previous lab from 13 onward (or select your mid-term project) and create a new branch on that lab called `lab-42`
* Find all the Mongoose queries you made in that lab, and in comments, write out an equivalent SQL query. For example:

```
/*
  SQL equivalent:
  SELECT TOP 1 * FROM ACCOUNTS WHERE tokenseed = token
*/
// Mongoose/MongoDB method in actual code
Account.findOne({ tokenSeed: token })...

```
 
 ## Stretch Goals
 * You can also include `Sequelize` queries
 * Try to make a **very basic app** that connects to your PostgresSQL database and make one Express POST route that creates a resource similar to any used in your lab


