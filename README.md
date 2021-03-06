# FBLA Mobile App 2018
### Logging In
Logging in is required to access the app. 
 This lets you view books, check in/check out books, and view checked out books and reservations.


There are currently two STUDENT test users currently, John Smith and Jane Doe.  
John Smith has a username of 1111111 (seven ones) and his password is "password" (without quotes).  
Jane Doe has a username of 2222222 (seven twos) and her password is "password" (without quotes).


There is currently one TEACHER test user, Mrs. Teacher.  Her username is 9999999 (seven nines) and password is "password" (no quotes)


All logins are sent over secure HTTPS, and are salted and hashed before being stored in the database, as per industry best practice rules.

### Checking out
Students are allowed to check out up to 5 books, while teachers can check out up to 120 books. 
 Books are due 3 weeks after they are checked out.
### Checking in
Checking in a book immediately marks it as available.

### Reservations
Reservations can be made on a book as long as the user doesn't have already have a reservation out on the book.

### Filling a reservation
When a reservation is filled, the book is automatically checked out in the user's name.

### Renewals
A user can renew a book up to 3 times, as long as there are no active reservations on the book at time of renewal.  
Each renewal grants an additional week of time with the book.
### API
The backend API was coded in C#, using Microsoft's ASP.​NET and Entity Framework Core.  
The site runs on Microsoft's cloud platform Azure at https://fblamobileapp.azurewebsites.net/.  Currently, the site displays the Swagger API documentation.

### To Download and Run the App
* Plugin the testing device to the computer
* Access the devices downloads from the computer file manager, then paste the apk titled "Librarian" into that folder
* On the phone, go to the downloads section of MyFiles, and tap on Librarian.apk
* Install the app, then go to the homescreen to open the app
	