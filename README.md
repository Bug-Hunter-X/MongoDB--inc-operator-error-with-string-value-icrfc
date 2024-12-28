# MongoDB $inc operator error with string value
This repository demonstrates an error that can occur when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment a numerical field by a specified value.  However, if you try to increment a field with a non-numerical value (e.g., a string), the operation will fail silently, and the field will not be updated.

**Bug:** The bug arises from attempting to increment a field with a string value using the `$inc` operator. 

**Solution:** Ensure that the value used with `$inc` is a number.
