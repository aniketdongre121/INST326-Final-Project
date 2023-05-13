# INST326-Final-Project
Group Members: Sana Amjad, Aniket DonGRE, Favor Umeobi, Joshua Santos
# Contact / Address Book Application
We thought about creating an Application that will have all contact information of a certain user and this application that will also hold a database of different contact information. 
We chose to create this application because it will help users to easily access all their contacts' information from one place, instead of having to search through multiple sources such as email, phone contacts, and social media. 

# How to run the Program
This program has two windows: a login window and a contact management application window. To run the program, you need to save the code in a file with a ".py" extension, then run it using a Python interpreter. Here are the steps:

1. Open a code editor such as VS Code or PyCharm, and create a new file.
2. Copy and paste the entire code into the file.
3. Save the file with a name, for example, "contact_manager.py".
4. Open a terminal or command prompt and navigate to the directory where you saved the file.
5. Run the program by typing "python contact_manager.py" in the terminal and press Enter.
6. The login window will appear, and you will be prompted to enter a username and password. Enter "admin" for the username and "password" for the password, then click the "Login" button.
7. If the username and password are correct, the contact management application window will appear. You can use the application to add, view, and delete contacts from a database.

# How to Use and Interpret the Program
To use the program, you first need to run it in a Python environment. You can do this by copying the code into a Python file and running it using a Python interpreter. Once the program is running, you will be prompted to log in using the username and password specified in the code.

After logging in, you will be taken to the contact management window. From here, you can add new contacts by filling in the fields in the "Add Contact" section and clicking the "Add" button. You can view all existing contacts by clicking the "View Contacts" button, which will display them in a message box. To delete a contact, click the "Delete Contact" button, which will open a popup window asking for the ID of the contact to be deleted.

The program uses SQLite to store contact information in a database. The "connect" function is used to establish a connection to the database and create a "contacts" table if it does not already exist. The "add_contact" function inserts new contacts into the table using the input values entered by the user. The "view_contacts" function retrieves all contacts from the database and displays them in a pretty table. The "delete_contact" function allows the user to delete a contact from the database based on its ID.


# Bibliography 

# Replit
This is the link to our shared Replit, where you can easily see our code, unit tests, output, etc

https://replit.com/join/rhnmbrfwss-sanaamjad1
