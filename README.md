# userSearch README file

### **File Path**

*C:\Users\User\QA\tests\Admin\userSearch.json*

### **General Description**

The program will login, go to Admin menu category and search for an existing user

### **Testing Method**

1. The program will verify first the presence of user1 (roiweinreb) on the users list.
2. The program will insert user2's name (Kostya Shyika) to the search box.
3. The program will verify user2 presence and the disappearance of user1 from the list.

### **Detailed Explanation**

1) Connects to the login page

2) Inserts user's email address

3) Inserts user's password

4) Clicks the login button
 
5) Waits for the home page to be uploaded
 
6) Verifies "Welcome to materials zone" text on the home page
 
7) Clicks on Admin menu category 
 
9) Verifies the current url
  
10) Verifies user search box presence
  
12) Types "Kostya Shyika" in the search box
  
14) Verifies the presence of "Kostya Shyika" on the list
  
15) Verifies the disappearance of "roiweinreb" from the list

#### **File Image** 

![usersearchimage](https://cloud.githubusercontent.com/assets/26378397/24261716/8b6e8820-1000-11e7-98e0-d5fa309124c5.png)
