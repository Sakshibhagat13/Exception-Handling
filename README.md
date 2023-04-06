# Exception-Handling


Question 1:


Create a user-defined checked exception called InsufficientFundsException. 
Create a class called Account with 2 fields: 
accountNumber: String 
balance: double 

and define the following 2 methods inside the Account class: 
deposit(amount): void 
withdraw(amount): double 
withdraw(amount) method throws the InsufficientFundException to the caller with suitable message. when the supplied amount is greater than the balance amount. 

Create an AccountDemo class with the main method and perform the following task: 
Create the Account class object by passing the Account number and minimum balance 500. You can deposit the amount into that account by invoking the deposit() method by passing the deposit amount as an argument. 
If you have a balance in your account, you have to withdraw the amount by invoking the withdraw() method by passing a suitable amount as an argument. But, if your requested amount is more than the available balance, handle the exception and print the proper message. 
Note: make sure the application should be terminated normally.


Question 2:


Handle exceptions in the number Problem statement: 
Get the input String from the user and parse it to an integer, if it is not a number it will throw NumberFormatException, Catch this exception and print "Entered input is not a valid format for an integer." or else print the square of that number. (Refer to Sample Input and Output). 

Sample input and output 
1: Enter an integer: 12 
The square value is 144 
The work has been done successfully 

Sample input and output 2: 
Enter an integer: Sakshi
Entered input is not a valid format for an integer. 
The work has been done successfully 

