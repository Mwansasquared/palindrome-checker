# panlidrome-checker

This is a simple palindrome checker program that checks if a given string is a palindrome.

*A palindrome is a word or sentence that's spelled the same way both forward and backward, ignoring punctuation, case, and spacing.*

The program has a function that converts the passed string to lowercase (but can also be converted to uppercase) and replaces special characters, such as *, ?, / placed in a regex, with an empty string (""), and then loops through the resulting string, both starting from the beginning and the end, comparing the values indexed at each end of the string.
