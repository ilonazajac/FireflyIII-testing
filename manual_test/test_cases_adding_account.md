# MANUAL TESTING: ADDING ACCOUNT  


## Test Case ID: TC001
### Test Case Name: Create a Default Asset Account

**Objective**: Verify that a user can successfully create a default asset account within Firefly III.

**Preconditions**:
- User is logged into Firefly III.

**Test Data**:
- Name: "Main Account"
- Currency: Euro
- Opening balance: 1000
- Opening balance date: 22.02.2024 [Tests's Date]
- Account role: Default asset account

**Steps to Execute**:
1. Navigate to the "Accounts" section and select "Asset accounts".
2. When the "Accounts" page opens, click the "Create an asset account" button.
3. In the "Name" field, enter "Main Account".
4. In the "Currency" field, choose EUR from the dropdown.
5. In the "Opening balance" field, enter "1000".
6. Set the "Opening Date" to today's date.
7. From the "Account role", select "Default asset account".
8. Click the "Store new asset account" button to create the account.
9. A success notification appears stating: "Success! New account "Main Account" stored!".


**Expected Result**:
- A notification of successful account creation will be displayed.
- The new account, "Main Account", is listed under the Asset Accounts section with a balance of 1,000.00 EUR.

**Actual Result**: 
- A notification of successful account creation is displayed.
- The new account, "Main Account" is listed under the Asset Accounts section with a balance of 1,000.00 EUR.

**Status**: Pass

**Tester**: Ilona Zając

**Test Date**: 22.02.2024

**Environment**:

Windows 11 Pro Version 22H2

Google Chrome Browser Version 117.0.5938.149 (Official Version) (64-bit)


## Test Case ID: TC002
### Test Case Name: Create a second Asset Account with te same name

**Objective**: Verify that a user can not successfully create a second asset account within Firefly III with the same name.

**Preconditions**:
- User is logged into Firefly III.

**Test Data**:
- Name: "Main Account"
- Currency: Euro
- Opening balance: 5000
- Opening balance date: 04.03.2024 [Tests's Date]
- Account role: Default asset account
  
**Steps to Execute**:
1. Navigate to the "Accounts" section and select "Asset accounts".
2. When the "Accounts" page opens, click the "Create an asset account" button.
3. In the "Name" field, enter "Main Account".
4. In the "Currency" field, choose EUR from the dropdown.
5. In the "Opening balance" field, enter "5000".
6. Set the "Opening Date" to today's date.
7. From the "Account role", select "Default asset account".
8. Click the "Store new asset account" button to create the account.

**Expected Result**:
- The "Name" field will be highlighted in red and the notification "This account name is already in use." will appear.
- There is no possibility to create a secon account with the same name.

**Actual Result**: 
- The "Name" field highlighted in red and the notification "This account name is already in use." appeared.
- There is no possibility to create a secon account with the same name.

**Status**: Pass

**Tester**: Ilona Zając

**Test Date**: 04.03.2024

**Environment**:

Windows 11 Pro Version 22H2

Google Chrome Browser Version 117.0.5938.149 (Official Version) (64-bit)


## Test Case ID: TC003
### Test Case Name: Create an Asset Account without filling in all mandatory "Name field

**Objective**: Verify that a user can not successfully create a default asset account within Firefly III without filling in the mandatory "Name" field.

**Preconditions**:
- User is logged into Firefly III.

**Test Data**:
- Currency: Euro
- Opening balance: 1000
- Opening balance date: 04.03.2024 [Tests's Date]
- Account role: Default asset account

**Steps to Execute**:
1. Navigate to the "Accounts" section and select "Asset accounts".
2. When the "Accounts" page opens, click the "Create an asset account" button.
3. Do not fill in the mandatory "Name" field.
4. In the "Currency" field, choose EUR from the dropdown.
5. In the "Opening balance" field, enter "1000".
6. Set the "Opening Date" to today's date.
7. From the "Account role", select "Default asset account".
8. Click the "Store new asset account" button to create the account.

**Expected Result**:
- The "Name" field will be highlighted in red and the notification "The name field is required." will appear.
- There is no possibility to create an account without filling the mandatory "Name" field.

**Actual Result**: 
- The "Name" field highlighted in red and the notification "The name field is required." appeared.
- There is no possibility to create an account without filling the mandatory "Name" field.
- 
**Status**: Pass

**Tester**: Ilona Zając

**Test Date**: 04.03.2024

## Test Case ID: TC004
### Test Case Name: Create an asset account with a negative opening balance

**Objective**: Verify that a user can not successfully create an asset account in Firefly III with a negative opening balance.


**Preconditions**:
- User is logged into Firefly III.

**Test Data**:
- Name: "Second Account"
- Currency: Euro
- Opening balance: -500
- Opening balance date: 26.02.2024 [Tests's Date]
- Account role: Default asset account

**Steps to Execute**:
1. Navigate to the "Accounts" section and select "Asset accounts".
2. When the "Accounts" page opens, click the "Create an asset account" button.
3. In the "Name" field, enter "Second Account".
4. In the "Currency" field, choose EUR from the dropdown.
5. In the "Opening balance" field, enter "-500".
6. Set the "Opening Date" to today's date.
7. From the "Account role", select "Default asset account".
8. Click the "Store new asset account" button to create the account.
9. A success notification appears stating: "Success! New account "Second Account" stored!".

**Expected Result**:
- A notification of successful account creation will be displayed.
- The new account, "Second Account", is listed under the Asset Accounts section with a balance of -500.00 EUR.

**Actual Result**: 
- A notification of successful account creation is displayed.
- The new account, "Second Account" is listed under the Asset Accounts section with a balance of -500.00 EUR.

**Status**: Pass

**Tester**: Ilona Zając

**Test Date**: 22.02.2024

**Environment**:

Windows 11 Pro Version 22H2

Google Chrome Browser Version 117.0.5938.149 (Official Version) (64-bit)

## Test Case ID: TC005
### Test Case Name: Create an asset account by entering letters in the "Opening Balance" field.

**Objective**: Verify that a user can not successfully create an asset account within Firefly III without by entering letters in the "Opening Balance" field.


**Preconditions**:
- User is logged into Firefly III.

**Test Data**:
- Name: Spare Account
- Currency: Euro
- Opening balance: Abcde

**Steps to Execute**:
1. Navigate to the "Accounts" section and select "Asset accounts".
2. When the "Accounts" page opens, click the "Create an asset account" button.
3. In the "Name" field, enter "Spare Account".
4. In the "Currency" field, choose EUR from the dropdown.
5. In the "Opening balance" field, enter "Abcde".

**Expected Result**:
- There is no possibility to enter letters in the "Opening Balance" field.
- There is no possibility to create an asset account by entering letters in the "Opening Balance" field.

**Actual Result**: 
- There is no possibility to enter letters in the "Opening Balance" field.
- There is no possibility to create an asset account by entering letters in the "Opening Balance" field.

**Status**: Pass

**Tester**: Ilona Zając

**Test Date**: 04.03.2024

**Environment**:

Windows 11 Pro Version 22H2

Google Chrome Browser Version 117.0.5938.149 (Official Version) (64-bit)


## Test Case ID: TC006
### Test Case Name: Create an asset account by entering an incorrect date format in the "Opening Balance Date" field.

**Objective**: Verify that a user can not successfully create an asset account within Firefly III without  by entering an incorrect date format in the "Opening Balance Date" field.

**Preconditions**:
- User is logged into Firefly III.

**Test Data**:
- Name: "My Account"
- Currency: Euro
- Opening balance: 1000
- Opening balance date: 04.03.20244 
- Account role: Default asset account

**Steps to Execute**:
1. Navigate to the "Accounts" section and select "Asset accounts".
2. When the "Accounts" page opens, click the "Create an asset account" button.
3. In the "Name" field, enter "My Account".
4. In the "Currency" field, choose EUR from the dropdown.
5. In the "Opening balance" field, enter "1000".
6. In the "Opening balance date" field, enter "04.03.20244"
7. From the "Account role", select "Default asset account".
8. Click the "Store new asset account" button to create the account.
9. A success notification appears stating: "Success! New account "My Account" stored!".

**Expected Result**:
- It should not be possible to create an asset account by entering the date format "04.03.20244" in the "Opening balance date" field.

**Actual Result**: 
- A notification of successful account creation is displayed.
- The new account, "My Account" is listed under the Asset Accounts section with a balance of 1,000.00 EUR.

**Status**: Fail

**Tester**: Ilona Zając

**Test Date**: 04.03.2024

**Environment**:

Windows 11 Pro Version 22H2

Google Chrome Browser Version 117.0.5938.149 (Official Version) (64-bit)

## Test Case ID: TC007
### Test Case Name: Create an asset account by entering an incorrect date format in the "Opening Balance Date" field.

**Objective**: Verify that a user can not successfully create an asset account within Firefly III without  by entering an incorrect date format in the "Opening Balance Date" field.

**Preconditions**:
- User is logged into Firefly III.

**Test Data**:
- Name: Spare Account
- Currency: Euro
- Opening balance: 7000
- Opening balance date: 44.03.2024 
- Account role: Default asset account

**Steps to Execute**:
1. Navigate to the "Accounts" section and select "Asset accounts".
2. When the "Accounts" page opens, click the "Create an asset account" button.
3. In the "Name" field, enter "Spare Account".
4. In the "Currency" field, choose EUR from the dropdown.
5. In the "Opening balance" field, enter "7000".
6. In the "Opening balance date" field, enter "44.03.2024"
7. From the "Account role", select "Default asset account".
8. Click the "Store new asset account" button to create the account.


**Expected Result**:
- It should not be possible to create an asset account by entering the date format "44.03.2024" in the "Opening balance date" field.

**Actual Result**: 
- After entering in the field "Date of opening balance": 44.03.2024, the date automatically changed to: 04.04.3204.
- A notification of successful account creation is displayed.
- The new account, "Spare Account" is listed under the Asset Accounts section with a balance of 1,000.00 EUR.

**Status**: Fail

**Tester**: Ilona Zając

**Test Date**: 04.03.2024

**Environment**:

Windows 11 Pro Version 22H2

Google Chrome Browser Version 117.0.5938.149 (Official Version) (64-bit)


## Test Case ID: TC008
### Test Case Name: Create an Expense Account

**Objective**: Verify that a user can successfully create an expense account within Firefly III.

**Preconditions**:
- User is logged into Firefly III.

**Test Data**:
- Name: "My current expenses"

**Steps to Execute**:
1. Navigate to the "Accounts" section and select "Expense account".
2. When the "Accounts" page opens, click the "Create an expense account" button.
3. In the "Name" field, enter "My current expenses".
4. Click the "Store new expense account" button to create the account.
5. A success notification appears stating: "Success! New account "My current expenses" stored!".

**Expected Result**:
- A notification of successful account creation will be displayed.
- The new account, "My current expenses", is listed under the Expense Accounts.

**Actual Result**: 
- A notification of successful account creation is displayed.
- The new account, "My current expenses" is listed under the Expense Accounts.

**Status**: Pass

**Tester**: Ilona Zając

**Test Date**: 22.02.2024

**Environment**:

Windows 11 Pro Version 22H2

Google Chrome Browser Version 117.0.5938.149 (Official Version) (64-bit)

## Test Case ID: TC009
### Test Case Name: Create an Expense Account with the same name as the existing asset account 

**Objective**: Verify that a user can not successfully create an expense account within Firefly III with the same name as the existing asset account.

**Objective**: Verify that a user can successfully create an expense account within Firefly III with the same name as the existing asset account.

**Preconditions**:
- User is logged into Firefly III.

**Test Data**:
- Name: "Main Account"
  
**Steps to Execute**:
1. Navigate to the "Accounts" section and select "Expense account".
2. When the "Accounts" page opens, click the "Create an expense account" button.
3. In the "Name" field, enter "Main Account".
4. Click the "Store new expense account" button to create the account.
5. A success notification appears stating: "Success! New account "My current expenses" stored!".

**Expected Result**:
- A notification of successful account creation will be displayed.
- The new account, "Main Account", is listed under the Expense Accounts.

**Actual Result**: 
- A notification of successful account creation is displayed.
- The new account, "My current expenses" is listed under the Expense Accounts.

**Status**: Pass

**Tester**: Ilona Zając

**Test Date**: 04.03.2024

**Environment**:

Windows 11 Pro Version 22H2

Google Chrome Browser Version 117.0.5938.149 (Official Version) (64-bit)

## Test Case ID: TC010
### Test Case Name: Create an Expense Account with invalid IBAN

**Objective**: Verify that a user can not successfully create an expense account within Firefly III with IBAN that does not exist.


**Preconditions**:
- User is logged into Firefly III.

**Test Data**:
- Name: "Travel expenses"
- IBAN: "11111111111111111111111111"

**Steps to Execute**:
1. Navigate to the "Accounts" section and select "Expense account".
2. When the "Accounts" page opens, click the "Create an expense account" button.
3. In the "Name" field, enter "Travel expenses".
4. In the "IBAN" field, enter: "11111111111111111111111111"
5. Click the "Store new expense account" button to create the account.


**Expected Result**:
- The "IBAN" field will be highlighted in red and the notification "This is not a valid IBAN" will appear.
- There is no possibility to create an account with invalid IBAN.

**Actual Result**: 
- The "IBAN" field highlighted in red and the notification "This is not a valid IBAN" appeared.
- There is no possibility to create an account with invalid IBAN.

**Status**: Pass

**Tester**: Ilona Zając

**Test Date**: 22.02.2024

**Environment**:

Windows 11 Pro Version 22H2

Google Chrome Browser Version 117.0.5938.149 (Official Version) (64-bit)
