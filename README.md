# Hack Nullable Integer Bug
This repository demonstrates an uncommon error related to nullable integers in Hack. The `foo` function attempts to add 1 to a potentially null integer, resulting in an exception.
The solution provides a way to handle the null value safely before performing the addition.

## Bug
The original code has a type error because it doesn't handle the case when x is null. 

## Solution
The solution uses a null coalescing operator (`??`) to provide a default value when x is null. 
