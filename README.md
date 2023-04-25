# Test Case Samples

Below are some Test Case samples that I wrote.

...........................

### Test login with correct credentials

**Descripion**

Check if the login works when a person uses a correct user and password.

**Stept to reproduce**
1) Go to www.webside.com/login
2) Add the correct user
3) Add the correct password
4) Press login button

**Expected results**

User should be able to login and is taken to his profile page.

**Test data**

User: mirela

Password: 123456

............................

### Test login with incorect user / password 

**Description**

Check if the login works when the user enters the incorect user/password.

**Step to reproduce**
1) Go to www.website.com/login
2) Add the incorect user/password
3) Press the login button

**Expected results**

The user should not be able to login and a pop up massage box shows the error: "Invalid credentials".

**Test Data**

User: mirela
Password: 0123456

.............................

### Test login with correct credentials and "Remember Me" check box selected

**Description**

Check if the user can access the profile page without reintroducing the credentials.

**Steps to reproduce**
1) Go to www.website.com/login
2) Add correct user and password 
3) Select the "Remember Me" check box
4) Press the login button
5) Once on the my profile page, turn back or close the window
6) Go again to www.website.con/login

**Expected resuts**

User should enter directly on the profile page, without entering the credentials again.

**Test Data**

User: mirela

Password: 123456

................................

### Test if the user can access the profile page by changing the URL

**Description**

Check if the user can access the profie page by adding "/my profile" in the URL.

**Stepst to reproduce**
1) Go to www.website.con/login 
2) Add the user and password
3) Press the login button
4) Copy the /my account URL
5) Open a new internet page
6) Paste the new URL
7) Press the enter button

**Exected results**

The user should connect directly to myaccount page.

**Test Data**

User: mirela

Password:123456

New URL: www.website.com/myaccount

..................................

### Test if the user can access the profile page by changing the URL and without being loged in

**Description**

Check if the user can access the profie page without being loged and by adding the "/my profile" in the URL.

**Stepst to reproduce** 
1) Go to www.website.con/login 
2) Add the user and password
3) Press the login button
4) Copy the my account-URL
5) Log out
5) Open a new internet page
6) Paste the new URL
7) Press the enter button

**Exected results**

The user should not connect to myaccount page, the login page should show.

**Test Data**

User: mirela

Password:123456

New URL: www.website.com/myaccount

...................................

### Test if search box allows introducing keywords

**Preconditions**

A Chrome browser should be available on the device.

**Description**

Check if the search box allows typing keywords.

**Step to reproduce**
1) Go to www.emag.ro
2) Click on the search box
3) Type the keyword

**Expected results**

User can type the keyword in the seach box.

**Test Data**

Keyword: aspirator

...........................

### Test the search functionality by entering an invalid keyword

**Description**

Test the search functionality by entering the keyword and verifying that no results are displayed.

**Steps to reproduce**

1) Go to Emag.ro
2) Add the keyword in the search field
3) Press the search button

**Expected results**

No results are displayed.

**Test Data**

keyword: gfgfhfhhgdd
