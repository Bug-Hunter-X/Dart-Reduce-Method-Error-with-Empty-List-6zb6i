# Dart Reduce Method and Empty Lists
This example demonstrates a common error when using the `reduce` method in Dart with an empty list. The `reduce` method requires at least one element; otherwise, it throws an `UnsupportedError`.  The solution shows how to handle this scenario gracefully.

## Bug
The `reduce` method throws an `UnsupportedError` when called on an empty list. This is a runtime error that needs to be handled to prevent crashes.

## Solution
The solution involves checking if the list is empty before applying the `reduce` method. If the list is empty, return a default value (in this case, 0).