# MANUAL TESTING: ADDING CURRENCY

## Test Case ID: TC001
### Test Case Name: Add a new currency

**Objective**: Verify that a user can successfully add a new currency within Firefly III.

**Preconditions**:
- User is logged into Firefly III.

**Test Data**:
- Name: Saudi rial
- Symbol: SR
- Code: SAR
- Decimal places: 2
- 
**Steps to Execute**:
1. Navigate to the "Options" section and select "Currencies".
2. When the "Currencies" page opens, click the "Create a new currency" button.
3. In the "Name" field, enter "Saudi rial".
4. In the "Symbol" field, enter "SR".
5. In the "Code" field, enter "SAR".
6. In the "Decimal places" field, enter "2".
7. Click the "Store new currency" button to create the account.
8. A success notification appears stating: "Success! Currency Rial created".

**Expected Result**:
- A notification of successful currency addition will be displayed.
- The new currency, "Saudi rial (SAR) (SR)", is listed under the Curriencies list.

**Actual Result**: 
- A notification of successful currency creation is displayed.
- The new currency, "Saudi rial (SAR) (SR)" is listed under the the Curriencies list.
  
**Status**: Pass

**Tester**: Ilona Zając

**Test Date**: 07.03.2024

**Environment**:

Windows 11 Pro Version 22H2

Google Chrome Browser Version 117.0.5938.149 (Official Version) (64-bit)
