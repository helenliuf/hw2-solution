# hw2

The homework will be based on this project named "Expense Tracker",where users will be able to add/remove daily transaction. 

## Compile

To compile the code from terminal, use the following command:
```
cd src
javac ExpenseTrackerApp.java
java ExpenseTrackerApp
```

You should be able to view the GUI of the project upon successful compilation. 

## Java Version
This code is compiled with ```openjdk 17.0.7 2023-04-18```. Please update your JDK accordingly if you face any incompatibility issue.

## Features
- Add a new transaction: First specify the amount and category. Then click on the Add transaction button. Adds the new transaction to the list and updates the total cost.
- Filter the transaction list by either amount or category: First specify the amount or category to be matched. Then click the corresponding Filter button. Highlights the matching transactions in the list.

- Remove a transaction: Select a transaction by clicking on its row. Then click on the Remove transaction button at the bottom of the window. Removes the transaction data, transaction row, and updates the total cost.
    - Remove transaction button is disabled unless a row is selected, making it hued out. If a row is selected, the button is enabled like the other buttons and no longer transparent. After a transaction is removed and no row is selected, the button is back to disabled.

- Real-time updates to the transaction table and total expense values
- Input validation for amount, category values
- Using MVC architecture to separate model, view and controllers
- Using filter on the expense table
- Adding validation on the filter inputs

## Technologies Used

- Java (Swing GUI)
- MVC Pattern
- JUnit (For testing)

## Build & Testing

1. With Apache Ant installed, run ```ant``` in the root directory containing the build.xml build file

2. Run ```ant compile``` to generate the class files

3. Run ```ant test``` to compile all unit tests and run them

## How to run (from Terminal, if compile instructions do not work):
After building the project, run: ```java -cp bin ExpenseTrackerApp```