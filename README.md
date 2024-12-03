## Explanation
Date Format Enforcement:

The input event is used to capture every change in the input field.
The formatDate() function ensures the date is formatted as YYYY/MM/DD.

## Backspace Handling:

The keydown event listens for the backspace key.
When backspace is pressed, the last character is removed from the value, and the formatDate() function is reapplied to ensure proper masking.

## Invalid Character Prevention:

The keypress event prevents any non-numeric characters from being entered.

## Maximum Length:

The maxlength="10" attribute ensures the input doesn't exceed 10 characters (for YYYY/MM/DD).
