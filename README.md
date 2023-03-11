# APIS-FOR-SPECIFIED-USERS
## Authentication
- Goodreads APIs
   - Register user API
   - Login user API
- bcrypt
  - bcrypt.hash()
  - bcrypt.compare()
1. Installing Third-party package bcrypt
Storing the passwords in plain text within a database is not a good idea since they can be misused, So Passwords should be encrypted

bcrypt package provides functions to perform operations like encryption, comparison, etc

bcrypt.hash() uses various processes and encrypts the given password and makes it unpredictable
bcrypt.compare() function compares the password entered by the user and hash against each other
Installation Command
 root@123:~/myapp# npm install bcrypt --save
 2. APIs for Specified Users
We need to maintain the list of users in a table and provide access only to that specified users

User needs to be registered and then log in to access the books

Register User API
Login User API
