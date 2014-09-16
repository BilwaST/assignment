Name:Bilwa.S.T
USN:1PI12IS026
Ques.No:3
source code file:asn2_3.c
Ques.Title:to print last login time and update login time every time the user login
Execution:
   gcc asn2_3.c
   ./a.out -f password.txt

In password.txt file the data will be stored in this form "username,password,login" so when user login we need to verify 
username and password first and then print their last login time.and we need to update the login details everytime
user login


Inputs:
1.first enter username without space in between
2.password

error:
Getting segmentation fault when we execute the program for second time for file spaces which are present due to two factors
1.for a deleting a line we are copying it into other file except the line to be deleted and then renaming it
2.we are even appending a line in file which is getting appended after some space
