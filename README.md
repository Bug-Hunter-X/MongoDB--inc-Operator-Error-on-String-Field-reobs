# MongoDB $inc Operator Error on String Field

This repository demonstrates a common error in MongoDB when using the `$inc` operator on a field that is not of a numerical type (e.g., a string). The `$inc` operator is specifically designed for incrementing numerical values.  Attempting to use it on a string results in an error.

**Bug:** The provided `bug.js` file shows how an incorrect query can be constructed that attempts to increment a string field. This results in a MongoDB error.

**Solution:** The `bugSolution.js` file demonstrates the correct way to handle such situations, including appropriate type checking or data transformation before using the `$inc` operator.

This example highlights the importance of understanding data types when working with MongoDB operators and emphasizes the need for proper error handling.