**Overview:**
This is a simple online banking system where users can hold different types of accounts as offered by the bank. The customers can perform operations according to the account type; e.g. deposit, withdraw, balance enquiry and transferring funds. The banking system manages the accounts by debiting the fees or crediting the profits. Both the administrator and the customer can print report on current account details.

**Course Information:**
This project was developed as part of the Object Oriented Programming (CS-116) at Ned University of Engineering and Technology. The course was completed during the Spring Semester First Year.

**Project Scope and Requirements:**

**Minimum Required Features:**
The application should contain the following:
Design: Basic Classes: Account, CheckingAccount, SavingAccount, Loan, Customer: 

**A.** The Account is a general account class that contains balance as instance variable, deposit, withdraw, and balanceEnquiry as instance methods. 

**B.** CheckingAccount is a subclass from the Account class that allows overdraft while withdrawing (making the balance go below zero up to the specified credit limit), by debiting the account balance with an overdraft fee. It has a creditlimit as an instance variable. 

**C.** The Saving Account is a subclass from the Account class that has an interest rate as an instance variable. The system credits the balance with monthly interest based on the account balance and the interest rate. 

**D.** The Loan Account is a subclass from the Account class that has principal amount, interest rate, loan duration in months as instance variables. The loan balance is debited by monthly interest each month based on the interest rate and the loan balance. 

**E.** Allow user to create an account with some basic information like username, password, first and last names, address, etc. 

**F.** Each customer can have any number of accounts of any type.

**G.** Maintain record of all account holders. Transaction history should be stored.

**H.** The banking system provide the customer with an interface to access all banking operations described above and review reports about transactions and current balance. 

**I.** A banking administrator can print a report about all customers and their current balances.

**Technology Stack:**
The project was built using the following technologies:

Programming Language: Python

Data Storage: File processing approach (using Python’s file handling)

Development Approach: Object-Oriented Programming (OOP)

**Team Collaboration:**
This project was developed as a team effort. Collaboration included sharing responsibilities for coding, testing, and documentation, as well as regular team meetings to ensure alignment and progress.

**Conclusion:**

This project, my second-ever Python project, was a valuable learning experience in practicing Object-Oriented Programming concepts in a team setting. By using Python's file processing capabilities, we were able to create a functional banking application without relying on a database system. The project reinforced our understanding of OOP, teamwork, and provided insights into managing data securely in a file-based system.
