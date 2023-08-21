0. Regex-ing
Write a function called filter_datum that returns the log message obfuscated:

1. Log formatter
Copy the following code into filtered_logger.py.

2. Create logger
Use user_data.csv for this task

Implement a get_logger function that takes no arguments and returns a logging.Logger object.

The logger should be named "user_data" and only log up to logging.INFO level. It should not propagate messages to other loggers. It should have a StreamHandler with RedactingFormatter as formatter.

Create a tuple PII_FIELDS constant at the root of the module containing the fields from user_data.csv that are considered PII. PII_FIELDS can contain only 5 fields - choose the right list of fields that can are considered as “important” PIIs or information that you must hide in your logs. Use it to parameterize the formatter.

3. Connect to secure database

4. Read and filter data
Implement a main function that takes no arguments and returns nothing.

5. Encrypting passwords
User passwords should NEVER be stored in plain text in a database.

6. Check valid password
Implement an is_valid function that expects 2 arguments and returns a boolean.
