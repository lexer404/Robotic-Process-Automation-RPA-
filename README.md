# CMPG323-PROJECT_4-37530399

### Prerequisites

Before you start, ensure you have the following software installed on your system:

- UiPath Studio (Version: Specify the version you're using)
- Microsoft Excel


# How the project should be used by users
In this automation, when you run it a pop up will show to allow the user to insert password and email. Reason for this was because I wanted to save no password in the code(UiPath Studio files). The other reason for this pop up is to accomodate for a different user signing in, so that the automation doesn't insert the same logins for different users.

After the credentials are entered another pop up window will show. This will let the user be able to select if they want to test for which table (Orders, Order Details, Products, Customers). Reason for the popup was to cater for when the user only wants to read in Products, so that they don't wait for the automation to do other tables before getting to the desired one.

After the choice was made for which table to test, the automation will login with the provided credentials. 

After loggin in, it will redirect to the page of the selected table. After that, a popup will show so that user can select to add, edit or delete.

When add is selected all the details(rows) will be automatically added.

# Reference List
[Reference List.docx](https://github.com/lexer404/CMPG323-PROJECT_4-37530399/files/13043384/Reference.List.docx)


When edit is selected, the first row will be edited.

When delete is selected, all the details(rows) will be automatically deleted and "TRUE" will be written to the "Result" column in Excel. Reason for this was because if a row can be deleted it simply means that it was successfully added.

