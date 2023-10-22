# CSE 15L Lab Report 2
## Amber Tse A16776236 10/22/2023

StringServer Code:
![Image](StringServer1.png)
![Image](StringServer2.png)

*******

![Image](add1.png)

The handleRequest method in my code gets called during this screenshot.\
The argument in the handleRequest method is called url and it is the url of the server.
The field arrlist, which is an arraylist to hold the entries from adding a message, starts
out as an empty arraylist before the add message request is made. The string numlist, 
which is the string format of all the entries in the arraylist, also starts out as an 
empty string. The array of strings called parameters is empty before the request is made. \
The value of arrlist is changed from this request to be [Hello]. numlist is also changed to be 
1. Hello

parameters gets updated to be {s, Hello}.

********

![Image](add2.png)


The handleRequest method in my code gets called during this screenshot.\
The argument in the handleRequest method is called url and it is the url of the server.
The field arrlist starts out as [Hello] before the add message request is made.
The string numlist, starts out as "1\. Hello". The array of strings called parameters 
is {s, Hello}. \
The value of arrlist is changed from this request to be [Hello, How+are+you]. numlist is also changed to be 
1. Hello 
2. How+are+you

parameters gets updated to be {s, How+are+you}.

********

![Image](keypaths.png)

Using ls while being in my .ssh directory shows the paths to both my public key, id_rsa.pub, and my private key, id_rsa.

Logging into ieng6 without password:

![Image](nopwd1.png)
![Image](nopwd2.png)

******

I didn't know before that multiple people are able to log into a remote computer at once. During lab, all the CSE15L students were using their ieng6 account to log into the 201, 202, or 203, computers, and multiple people were able to be connected to a computer at once. I also learned the components of a URL and how to write code that changes the server's output as you add a query in the URL. 


