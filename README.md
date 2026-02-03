# EXPERIMENT-5

AIM:- To study and implement the concept of Dictionary in Python.

THEORY: A dictionary in Python is a built-in data structure that stores data in the form of key–value pairs, where each key acts as a unique identifier for its corresponding value. Dictionaries are created using curly braces {} or the dict() function and allow efficient storage and retrieval of information. The keys in a dictionary must be unique and immutable, while the values can be of any data type such as numbers, strings, lists, or even other dictionaries. One of the major advantages of dictionaries is their mutability, which means values can be updated, new key-value pairs can be added, and existing entries can be removed as required. Common operations include accessing elements using keys, updating values, deleting entries using commands like del or pop(), and traversing through the dictionary using loops. In practical applications, dictionaries are widely used for storing student records, managing login systems, counting word frequencies, and organizing structured data efficiently. Thus, Python dictionaries provide a flexible and powerful way to handle large and complex datasets in programming.

--->ALGORITHM FOR PROBLEM STATEMNT 1:-

Start the program.

Create a dictionary named products containing product names as keys and their prices as values.

Display the original dictionary using the print() function.

Update the price of the product "Keyboard" by assigning a new value (85) to its key.

Display the updated dictionary using the print() function.

End the program.

--->ALGORITHM FOR PROBLEM STATEMNT 2:-

Start the program.

Create a dictionary named student_marks with student names as keys and their marks as values.

Ask the user to enter the name of the student to be searched using the input() function and store it in search_name.

Use the get() method of the dictionary to search for the entered name.

If the name is found, display the corresponding marks.

If the name is not found, display the message "Student not found".

End the program.

--->ALGORITHM FOR PROBLEM STATEMNT 3:-

Start the program.

Create a dictionary named user_credentials containing usernames as keys and their corresponding passwords as values.

Prompt the user to enter their username using the input() function and store it in the variable username.

Prompt the user to enter their password using the input() function and store it in the variable password.

Use the get() method of the dictionary to retrieve the password associated with the entered username.

Compare the retrieved password with the entered password using an if-else statement.

If both passwords match, display the message "Login successful!".

Otherwise, display the message "Invalid username or password.".

End the program.

--->ALGORITHM FOR PROBLEM STATEMNT 4:-

Start the program.

Create a dictionary named marks with student names as keys and their respective marks as values.

Use the max() function along with key = marks.get to find the key (student name) having the highest value (maximum marks).

Store the result in the variable topper.

Display the name of the topper using the print() function.

Display the marks of the topper by accessing the dictionary using marks[topper].

End the program.

CONCLUSION:- From this experiment, we learned about the concept and practical use of dictionaries in Python programming. We successfully created dictionaries to store data in key–value pair format and performed various operations such as accessing values, updating records, searching for elements, validating user login, and finding the maximum value. The experiment helped in understanding how dictionaries provide an efficient and flexible way to organize and manage structured data. Thus, Python dictionaries are very useful in real-life applications like record management, authentication systems, and data processing.
