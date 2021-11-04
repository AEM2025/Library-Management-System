# Library-Management-System

## Description:
The library, contains tens of thousands of books and members which must be organized in order to prevent chaos. The program will allow performance of the actions needed to manage the library in a simple and comfortable way. The actions will include addition/removal of books, addition/removal of members, member and book searches, and much more.

The system will support two distinct types of users Librarians and Readers. For each user (reader/librarian) exists a unique Id and password, used for user authentication to prove identity of the user. Reader should have (FirstName, LastName, Address, Cellphone, Email, isBlocked).


Here are the types and the actions available for each type of users:
1. Librarians that can:
   - Add/Remove a book from the library.
   - Add/Remove a user from the library.
   - Search for books or members.
   - Add/Remove users from Book- Order list
   - Blocking of users who return books late
   - Rent a book.

2. Readers that can:
   - Searching of books or users.
   - Addition of self to Book- Order list.
   - Rent or buy a book.

Request should have : 
 - ID 
 - ISBN
 - Request date
 - Due date
 - It has two types
   - Buy  
   - Borrow

Books should have :
 - ISBN
 - Title 
 - Author 
 - Location
 - Number of Copies 
 - Genre 
 - price

## Quickstart:
- Download <a href="https://visualstudio.microsoft.com/downloads/" target="_blank"> Microsoft Visual Studio </a> version 2010 or above.

## Notes:
- I did this project with my teamwork. My role was develop C++ GUI windows form application.
- Name and Password for Admin user can be found in <i> OOP -> Accounts.txt </i>. You can change them to whatever you want.

## How to Use?
1. To run the project and see the full design follow this steps:
   - Download the project in your machine.
   - Open <i>OOP.sln</i> file.
2. If you want to try using the program : <i>Debug -> OOP.exe </i>
