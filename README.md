Purpose:

The application is designed to manage a contact directory, allowing users to add, modify, and view contact information such as name, surname, and phone number.
Features:

Add Contacts: Users can enter the details of new contacts, including name, surname, and phone number. The application checks for valid phone numbers (8 to 12 digits) before adding them to the list.
Modify Contacts: Users can modify existing contact information, including changing the name, surname, or phone number. The application prompts users to specify which contact to edit based on the index and allows them to choose the field to update.
View Contacts: The contact list can be displayed, showing the name, surname, and phone number of each contact.
Contact Storage: All contact information is stored in memory (using lists) for the duration of the program's execution.
Data Structure:

The system uses three separate lists to store contact information:
names: A list for storing the names of contacts.
surnames: A list for storing the surnames of contacts.
phone numbers: A list for storing the phone numbers.
These lists are managed by the program to track the total number of contacts, allowing for easy modification or display.
Input Validation:

The phone number is validated to ensure that it contains only digits and is within the correct length (8 to 12 characters). This is done by checking the length and using the .isdigit() method to confirm the number is numeric.
Menu-Based Interaction:

The program provides a simple text-based menu that allows users to:
Add new contacts
Modify existing contacts
View all contacts in the directory
Quit the program
Users interact with the program via the console, entering their choices from the menu.
Storage Limitation:

The system has a maximum number of contacts it can hold, which is set to 100. Once this limit is reached, no more contacts can be added.
Error Handling:

The application checks for valid inputs such as numeric phone numbers and ensures the contact index is within the valid range when modifying a contact. If invalid data is entered, appropriate error messages are displayed to guide the user.
