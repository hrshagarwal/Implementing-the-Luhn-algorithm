Credit Card Number Validator
Validates credit card numbers using the Luhn Algorithm.

Description
Checks if a card number is valid by performing the Luhn checksum.

How it works
Double every second digit from the right.

If doubling results in a two-digit number, add its digits.

Sum all digits.

Valid if total sum is divisible by 10.

Parameters:
card_number: Card number as a string.

Returns
True if valid, False otherwise.
