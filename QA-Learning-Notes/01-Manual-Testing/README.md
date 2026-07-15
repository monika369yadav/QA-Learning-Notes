# Manual Testing Fundamentals

**# Introduction to Manual Testing**


## What is Manual Testing?

Manual Testing is a type of software testing where a tester checks the application manually without using any automation tools or scripts.

The tester behaves like a real user and verifies whether the application works as expected.

## Simple Definition

Manual Testing means checking a software or application manually to find bugs before it is released to users.

## Real-Life Example

Imagine you buy a new TV remote.

Before selling it, the company checks:
- Does the Power button work?
- Does the Volume button increase and decrease the sound?
- Does the Mute button work?
- Does every button respond correctly?

A person presses every button one by one to verify everything. This is similar to Manual Testing.

## Software Example

Suppose there is a login page. It contains:
- Email field
- Password field
- Login button

A tester manually enters:
- Email: `monika@gmail.com`
- Password: `Password123`

Clicks Login.

- If the user reaches the dashboard successfully → ✅ Test Passed
- If an error appears even though the credentials are correct → ❌ Bug Found

## Daily Life Example

Imagine you order food from Zomato or Swiggy. You check:
- Is the restaurant name correct?
- Is the food image visible?
- Can you add items to the cart?
- Is the total price correct?
- Does the payment complete successfully?

You are actually performing Manual Testing as a user.

## Why Do We Need Manual Testing?

If software is released without testing, users may face problems such as:

- Login not working
- Payment failure
- Wrong calculation
- App crashing
- Buttons not working
- Incorrect data displayed

Manual Testing helps find these problems before customers do.

## Goal of Manual Testing

- Find bugs
- Improve software quality
- Verify requirements are met
- Ensure a good user experience
- Deliver a reliable product

## Simple Scenarios

### Scenario 1: Login Page

**Steps:**
1. Open the website.
2. Click Login.
3. Enter a valid email.
4. Enter the correct password.
5. Click Login.

**Expected Result:** The user should successfully log in and reach the Home Page.

**Actual Result (Bug Example):** Instead of opening the Home Page, an error appears: *"Invalid Password"* — even though the password is correct.

**Conclusion:** This is a Bug because the application is not behaving as expected.

### Scenario 2: Add to Cart

**Steps:**
1. Open any product.
2. Click Add to Cart.

**Expected Result:** The product should be added to the shopping cart.

**Actual Result:** Nothing happens after clicking the button.

**Result:** Bug Found

### Scenario 3: Forgot Password

**Steps:**
1. Click Forgot Password.
2. Enter your registered email.
3. Click Send OTP.

**Expected Result:** OTP should be sent to the registered email.

**Actual Result:** No OTP is received.

**Result:** Bug Found

## Characteristics of Manual Testing

- Performed by a human tester
- No coding is required
- No automation tools are used
- Easy for beginners to learn
- Helps identify UI, usability, and functional issues

## Advantages

- ✅ Easy to learn
- ✅ No programming knowledge required
- ✅ Best for exploratory testing
- ✅ Best for UI testing
- ✅ Helps understand user experience

## Disadvantages

- ❌ Time-consuming
- ❌ Repetitive work
- ❌ Human errors are possible
- ❌ Not suitable for testing the same feature repeatedly

## Interview Questions

**Q1. What is Manual Testing?**

Manual Testing is the process of testing software manually without using automation tools. A tester checks whether the application works according to the requirements and reports any bugs found.

**Q2. Why is Manual Testing important?**

Manual Testing helps identify bugs, verify software functionality, improve user experience, and ensure the application meets business requirements before release.

**Q3. Can Manual Testing be replaced by Automation Testing?**

No. Automation Testing is useful for repetitive tasks, but Manual Testing is still essential for exploratory testing, usability testing, and evaluating the overall user experience.

## Key Points to Remember

- Manual Testing is performed by a human tester.
- No coding is required.
- The goal is to find bugs before users do.
- The tester verifies that the application behaves as expected.
- Manual Testing improves software quality and user satisfaction.
