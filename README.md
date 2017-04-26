# storefront_cli

Explorer Mode
- Before starting: Make sure you read the ActiveRecord Guides. Specifically Basics and Querying
- How many users are there?
- What are the 5 most expensive items?
- What's the cheapest book?
- Who lives at "6439 Zetta Hills, Willmouth, WY"? Do they have another address?
- Correct Virginie Mitchell's address to "New York, NY, 10108".
- How much would it cost to buy one of each tool?
- How many total items did we sell?
- How much was spent on books?

Adventurer Mode
- Simulate buying an item by inserting a User from command line input (ask the user for their information) and an Order for that User (have them pick what they'd like to order and other needed order information).
- What item was ordered most often? Grossed the most money?
- What user spent the most?
- What were the top 3 highest grossing categories?

Epic Mode
- Create a new table and model to store reviews of items in the sqlite3 console.
- The reviews table should contain an item_id, a user_id, an integer value from 1-5 that gives the star rating, and text that contains the review.
- Create a command line interface that allows a user to find themselves by email address, pick an item they've ordered and leave a review on it.

Legendary Mode
- Write tests for each of your models and each of the methods that answer the above questions.
