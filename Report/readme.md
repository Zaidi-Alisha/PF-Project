Proposal idea:Our project Health Gear is a chatbot which aims to access a user with health and medical needs.It recommends medicines according to the symptoms provided by the user.This idea was chosen by us to assist people who cannot afford expensive medical treatments.Our HealthBot aims to bridge this gap by providing cost-effective assistance and guidance.It also ensures that individuals can seek assistance whenever they need it, without having to schedule appointments or visit healthcare facilities during specific hours.Along with it our application will allow users to rapidly learn about the condition they are experiencing and how it may be handled.Our healthbot will work by displaying a series of options related to health which this chatbot can help with.The user will select the problem he is going through an based on those problems our Healthbot will provide home remedies and recommended medicines.


Data structures used:The primary data structure used in our code is a multidimensional array for the printing of table.The menu of health-related options is represented using an array. Each option is a string, and the options are organized into rows and columns. For instance, "Fever" corresponds to row 0, column 0.The print_table function uses nested loops to iterate through the array and print the health information table in a structured format. It utilizes the rows and columns to display the options neatly.Another similar array (CoughTable) is used specifically for information related to cough types. This array follows the same structure and is printed using the print_CoughTable function.We have added it so that we can modify or extend the list of health options. Additional symptoms or conditions can be added by simply updating the array initialization.Moreover efficient retrieval of health options from the array is possible due to the use of indices, which enhances the program's overall performance.

Major Algorithms and logics used:
Print Table Function (print_table and print_CoughTable):
It uses nested loops to iterate through the 3D array and print the health information table or cough table.Array(rows * cols)involves nested loops iterating over rows and columns.
Cough Function (cough):
It involves a series of conditional statements to implements a decision tree based on user input to identify the type of cough and provides detailed information and recommendations.
Blood Pressure Function (BloodPressure):
The function involves nested conditional statements, to determine the user's blood pressure status based on input values

Chance of Improvement:
Break down the program into smaller functions to enhance readability, maintainability, and code reuse.
Consider using dynamic data structures (e.g., linked lists, dynamic arrays) if the program needs to handle a dynamic set of symptoms or conditions.
Clearer instructions, error messages, and enhanced user experience can improve interaction with users.

