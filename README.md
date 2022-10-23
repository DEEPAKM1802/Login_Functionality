# login_credential_verfiy
This project is to take valid username and password from  user and add it to file 
When the user chooses to Register

---> email/username should have "@" and followed by "."
      eg:- sherlock@gmail.com
            nothing@yahoo.in

---> it should not be like this 
       eg:- @gmail.com
            there should not be any "." immediate next to "@"
            eg:- my@.in
            it should not start with special characters and numbers
eg:- 123#@gmail.com

---> password (5 < password length > 16)
              Must have minimum one special character,
              one digit,
              one uppercase, 
              one lowercase character 

Stage 2 
  Once the username and password are validated, store that data in a file


Stage 3
Login
 When the user chooses to Login, check whether his/her credentials exist in the file or not based on the user input. 
If it doesn’t exist then ask them to go for Registration or 
If they have chosen forget password you should be able to retrieve their original password based on their username provided in the user input
or else you can ask them to provide a new password
(only if their username matches with the data exists in the file)
If nothing matches in your file you should ask them to Registration
(Since they don't have an account)
