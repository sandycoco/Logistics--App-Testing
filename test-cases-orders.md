# Logistics App - QA Test Cases

## Test Case 1: Login with Valid Credentials
- **Test Case ID**: TC001
- **Title**: Verify login with valid credentials
- **Precondition**: User has a registered account
- **Steps**:
  - Open the app
  - Enter valid username and password
  - Tap "Login"
- **Expected Result**: User is redirected to the dashboard

---

## Test Case 2: Login with Invalid Credentials
- **Test Case ID**: TC002
- **Title**: Verify login with invalid credentials
- **Precondition**: User enters incorrect password
- **Steps**:
  - Open the app
  - Enter valid username and wrong password
  - Tap "Login"
- **Expected Result**: Error message displayed, user remains on login screen

---

## Test Case 3: Create Delivery Order
- **Test Case ID**: TC010
- **Title**: Verify new delivery order creation
- **Precondition**: User is logged in
- **Steps**:
  - Navigate to "Create Order"
  - Fill in pickup and drop-off details
  - Submit order
- **Expected Result**: Order is saved and visible in "Active Orders"

---

## Test Case 4: Push Notification for Order Status
- **Test Case ID**: TC020
- **Title**: Verify push notification for order status update
- **Precondition**: User has an active order
- **Steps**:
  - Create an order
  - Change order status from backend (e.g., "In Transit")
- **Expected Result**: User receives notification with updated status
