# Bank App
**Project Description for Resume: Bankist App**

I. **Project Overview:**
The Bankist App is a web application that simulates banking operations, allowing users to manage their accounts, make transactions, and view their balance and transaction history. The app is built using JavaScript and interacts with the DOM to display user interface elements and handle user interactions.

II. **Key Features:**
1. User Authentication: Users can log in to their accounts by providing their username and PIN. Invalid logins are handled with appropriate error messages.

2. Account Overview: After logging in, users are presented with an account overview displaying their name, balance, and a summary of income, expenses, and interest earned.

3. Transaction History: Users can view a list of their past transactions, including deposits and withdrawals. Each transaction entry shows the type of transaction, date, and amount.

4. Transfer Funds: Users can transfer funds to other accounts by providing the recipient's username and the amount to be transferred. Transfers are reflected in both the sender's and recipient's transaction history.

5. Request Loan: Users can request a loan, provided they have a history of regular deposits. Once approved, the loan amount is added to their account balance.

6. Close Account: Users can close their accounts by confirming their username and PIN. Closing an account permanently removes it from the system.

7. Sort Transactions: Users can toggle between sorting transactions in ascending or descending order based on their amount.

III. **Data Structure:**
The app uses four different accounts, each represented as an object with properties such as owner's name, movements (transactions), interest rate, PIN, and currency. Account data is stored in an array named "accounts."

IV. **Key Functions:**
1. `displayMovements`: This function displays a list of transactions for a given account, including their type (deposit or withdrawal), date, and amount. It can sort the transactions if needed.

2. `calcDisplayBalance`: This function calculates and displays the current account balance based on its movements (transactions).

3. `calcDisplaySummary`: This function calculates and displays the total income, total expenses, and total interest earned for a given account.

4. `formatMovementDate`: This function formats a given date into a human-readable format, such as "Today," "Yesterday," or "X days ago."

5. `formatCur`: This function formats a numeric value into a currency format based on the locale and currency code.

6. `createUserNames`: This function generates a unique username for each account based on the owner's name.

7. `startLogOutTimer`: This function initiates a timer that automatically logs out the user after a specified duration of inactivity.

V. **Technologies Used:**
1. JavaScript: The core programming language used to build the application's logic and handle user interactions.

2. HTML and CSS: The markup and styling languages used to structure and design the user interface.

3. DOM Manipulation: Interacting with the Document Object Model (DOM) to dynamically update the UI based on user actions.

VI. **Key Takeaways:**
The Bankist App project showcases proficiency in JavaScript, DOM manipulation, and handling user interactions. It demonstrates the ability to build functional web applications with user authentication and data manipulation features.
