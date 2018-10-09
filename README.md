 # Bank_Tech_Test_Ruby

 [![Build Status](https://travis-ci.com/Alastair2D/bank-tech-test-ruby.svg?branch=master)](https://travis-ci.org/Alastair2D/bank_tech_test_ruby)

## Specification

### Requirements

* You should be able to interact with your code via a REPL like IRB or the JavaScript console.  (You don't need to implement a command line interface that takes input from STDIN.)
* Deposits, withdrawal.
* Account statement (date, amount, balance) printing.
* Data can be kept in memory (it doesn't need to be stored to a database or anything).

### Acceptance criteria

**Given** a client makes a deposit of 1000 on 10-01-2012  
**And** a deposit of 2000 on 13-01-2012  
**And** a withdrawal of 500 on 14-01-2012  
**When** she prints her bank statement  
**Then** she would see

```
date || credit || debit || balance
14/01/2012 || || 500.00 || 2500.00
13/01/2012 || 2000.00 || || 3000.00
10/01/2012 || 1000.00 || || 1000.00
```


### User Stories
* US1. As a customer, so I can store my money, I want to able to make a deposit
* US2. As a customer, so I can access my money, I want to be able to make a withdrawl
* US3. As a customer, so I can see the details of my account, I want to be able to print a statement

### Features
Must-Have Features:  Deposit, Withdraw, Print_Statement
Nice-to-Have Features: Store interactions in memory

### User Interactions 
* UI1. Account.new - Create a new instance of an Account
* UI2. Account.deposit(date, amount) - Make a deposit & update balance
* UI3. Account.withdraw(date, amount) - Make a withdrawl & update balance
* UI4. Account.statement - Prints statement

### Domain Model

