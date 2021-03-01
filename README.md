# Budget Tracking App

## Table of Contents:

1. [Concept Description](#concept-description)
2. [Wire Frames](#wireframes) <br/>
• [Home Page](#home-page) <br/>
• [Purchases Page](#purchases-page) <br/>
• [Spending List Page](#spending-list-page) <br/>
• [Spending Summary Page](#spending-summary-page) <br/>
• [Budget Page](#budget-page) <br/>
3. [Database Diagram](#database-diagram)
4. [User Stories](#user-stories)
5. [Use Cases](#use-cases)
6. [Requirements List](#requirements-list)
7. [UML Diagram](#uml-diagram)



## Concept Description
The purpose of the app is to help individuals overview their spending to make better financial decisions. Just the act of writing down what you spend is enough to help you become wiser with your money. The app will focus on awareness through logging purchases and monthly expenses. The goal is to create an application with modular code that can be easily transferred to a mobile application.

## Wireframes:

#### Home Page
![Home Page](https://github.com/jonathanrhoads/budget-tracker/blob/main/images/home.jpg "Home Page")

#### Purchases Page
![Purchases Page](https://github.com/jonathanrhoads/budget-tracker/blob/main/images/purchase.jpg "Purchases Page")

#### Spending List Page
![Spending List](https://github.com/jonathanrhoads/budget-tracker/blob/main/images/spendingList.jpg "Spending List")

#### Spending Summary Page
![Summary Page](https://github.com/jonathanrhoads/budget-tracker/blob/main/images/summary.jpg "Summary Page")

#### Budget Page
![Budget Page](https://github.com/jonathanrhoads/budget-tracker/blob/main/images/budget.jpg "Budget Page")


## Database Diagram
![DB Diagram](https://github.com/jonathanrhoads/budget-tracker/blob/main/images/DBDiagram.jpg "DB Diagram")


## User Stories
•	As a young adult, I want an app that aggregates my purchases, so that I can maintain records in one place.
•	As a transitioning military member, I want to know the difference between what I spend and my budget, so I can avoid going into debt.
•	As a career changer who is moving, I need to know the difference between what I expect to spend and what I actually spend so that I can adjust my budget.
•	As a financially educated individual, I want an overview of where my money is going so that I can maintain or change spending habits.

## Use-Cases
1.	Given a purchase, when the user has time then accept the information on the purchase.
2.	Given an income, when the user wants to find the difference between amount spent and income, then display that difference.
3.	Given monthly expenses, when the user inputs them, then show the total.
4.	Given monthly expenses, when the user has projected expenses that differ from actual expenses, display that difference for each category, subcategory, and total.
5.	Given purchase inputs, when a user wants to see the overview of purchases, display different formats for the user to interact with.
6.	Given purchase information, when the user wants to see them all in a order, display the list of purchases.
7.	
## Requirements List
1.  The system shall accept the users purchase information. <br/>
•   The software shall input that purchase information into the database to be retrieved later.<br/>
•   The software shall populate a list of purchases.<br/>
2. The user should be able to view the purchases in different formats like a pie chart, bar chart, and calendar.<br/>
•   The software shall pull that data out and organize it on different variables such as price, category, and date.<br/>
3. The user shall be able to input monthly expenses and income. <br/>
•   The system shall calculate the difference between income and monthly expenses.<br/>
•   The software shall send the monthly expenses to the database to be retrieved later.<br/>
•   The software shall display total expenses for each category and for all categories combined.<br/>
4. The user should be able to log back in and view all data previously input.<br/>
•    The system shall pull data based off of a user identification.<br/>

## UML Diagram
![UML Diagram](https://github.com/jonathanrhoads/budget-tracker/blob/main/Requirements/uml.jpg "UML Diagram")
