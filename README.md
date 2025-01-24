# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries.  The `$inc` operator is designed to increment a numerical field by a specified value. However, providing a non-numerical value will result in an error or unexpected behavior.

## Bug Description
The provided code incorrectly uses the `$inc` operator, attempting to increment the `count` field by the string value '1'.  This will throw an error.

## Solution
The solution ensures that the value used with the `$inc` operator is a number.