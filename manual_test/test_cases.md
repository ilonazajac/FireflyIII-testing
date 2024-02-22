## Test Case ID: TC001
### Test Case Name: Create a Default Asset Account in Firefly III

**Objective**: Verify that a user can successfully create a default asset account within Firefly III.

**Preconditions**:
- User is logged into Firefly III.
- User is on the "Accounts" -> "Create an asset account" page.

**Test Data**:
- Name: "Main Account"
- Currency: Euro
- Opening balance: 1000
- Opening balance date: 22.02.2024 [Tests's Date]
- Account role: Default asset account

**Steps to Execute**:
1. Navigate to the "Accounts" section and select "Asset account".
2. When the "Account" page opens, click the "Create an asset account" button.
3. In the "Name" field, enter "Main Account".
4. In the For "Currency" field, choose EUR from the dropdown.
5. In the "Opening balance" field, enter "1000".
6. Set the "Opening Date" to today's date.
7. From the "Account role", select "Default asset account".
8. Click the "Store new asset account" button to create the account.
9. A success notification appears stating: "Success! New account "Main Account" stored!".


**Expected Result**:
- User is redirected to the account summary page.
- A success notification appears stating "Account has been created successfully".
- The new account, "My Cash Account", is listed under the Cash Accounts section with a balance of 1000 USD.

**Actual Result**: [To be filled out after test execution]

**Status**: [Pass/Fail] (To be marked after test execution)

**Notes**: [Any additional information]

**Tester**: [Name of the tester]
**Test Date**: [Date of test execution]