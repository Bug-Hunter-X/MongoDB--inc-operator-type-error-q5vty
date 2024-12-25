# MongoDB $inc operator type error
This example demonstrates an incorrect usage of the `$inc` operator in a MongoDB update operation, resulting in a type error.
The `$inc` operator is used to increment a numerical value in a document. However, in this example, a string value ("1") is provided instead of a number (1), leading to an error.