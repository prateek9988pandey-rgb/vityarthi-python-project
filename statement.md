**1**. ****Introduction****

This project is a simple Python-based currency converter tool that allows users to convert between US Dollars (USD) and Indian Rupees (INR).
It is designed for beginners learning Python input handling, validation, functions, and loops.

**2**. ****Objectives****

The main goals of this program are:

To convert currency values between USD and INR.

To allow the user to update the exchange rate at any time.

To ensure safe and user-friendly input handling.

To demonstrate the use of functions, loops, and basic validation in Python.

**3**. ****Features****
✔ USD → INR Conversion

Converts a user-entered USD amount into Indian Rupees using the active exchange rate.

✔ INR → USD Conversion

Converts a user-entered INR amount into US Dollars.

**✔ Dynamic Exchange Rate Setup
**
Users can:

accept the default exchange rate, or

enter a new custom rate.

**✔ Input Validation
**
The program ensures:

only numeric values are accepted

negative numbers are rejected

invalid menu choices are handled properly

**✔ Interactive Loop
**
The program continues running until the user chooses to exit.

**4**. ****Program Flow****

Program starts and displays a welcome message.

User sets or confirms the exchange rate (default: 89.62 INR per USD).

**The main menu appears**:

1 → USD to INR

2 → INR to USD

3 → Change exchange rate

4 → Exit

Based on user choice, the program performs the selected operation.

The menu returns until the user selects Exit.

**5**. ****Key Functions****
usd_to_inr(amount_usd, rate)

Multiplies the USD amount by the exchange rate.

inr_to_usd(amount_inr, rate)

Divides the INR amount by the exchange rate.

get_valid_amount()

Ensures valid numeric and non-negative input.

get_valid_rate(default_rate)

Ensures exchange rate is a positive numeric value.

currency_converter_tool()

The main driver function that controls menu navigation and conversion operations.

**6**. ****Technologies Used****

Python 3

Basic input/output

Loops and conditions

Modular function structure

**7**. ****Conclusion****

This currency converter program demonstrates the fundamentals of user interaction, error handling, and modular programming in Python. It can be extended further into a graphical interface or integrated with real-time exchange rate APIs.
