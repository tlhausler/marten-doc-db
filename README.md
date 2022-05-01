# Document Database Project

## Context

The project was to create a final project for my Modern Databases class.  I was given leeway to decide what technologies to use and the functionality of the project.  I decided to create a mock banking application that would display a user's balance, pending transactions, and their amount.  The balance would also take into account the pending debits.

## Action

I opted to use Marten DB for this project.  I implemented the library into the project and built several classes that would handle accounts, transactions, and members. I configured a connection string to a postgres database and conducted all code for creating objects and displaying information in a using statement for the document db.  The project uses a console to display the information for a given user, showing pending transaction information as well as balance before and after pending debits were taken into account.  I created a single member with transactions and an account and save him to the database.  I then display his starting balance, and then call methods to calculate the total of pending debits and his balance after debits are taken into consideration.  I set his balance to the after amount and update the document db. 

## Result and Reflection
The project functioned as intended, that being just a simulated transaction log from a bank.  It created the document db as intended and was able to be updated.  

I found Marten made working with document databases extremely easy.  Obviously, a simulated application with limited data isn't the most useful, but it could be expanded upon and made more functional.  I feel like I would've liked more time working with document databases and learning about their usefulness in real world scenarios.  I learned that I enjoyed working with non-relational database approaches and would like to learn more about them in the future.
