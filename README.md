# User-profile
This Project is Created using HTML, CSS and JavaScript.

-----> Functionalities

I am using cookie-based logic, which allows this project to run serverless.

--> Registration:-
When the user registers himself after filling up the registration form, javascript will save all the data in a browser in for of cookies, a password will be converted to Base64 before saving.

--> Login:-
On login, javascript will match the information with the cookies, if matched then a new session cookie will be generated, and the user will be redirected to the Profile Page.

--> Password-Change:-
On the profile page, the password change button can be found. By filling up the password change form, javascript will remove the existing password cookie, and saves the new password in the base64 form.

--> Password-reset:-
The password reset form can be found on the login page, a user needs to fill up the email address, then javascript will check if an email exists in a cookie. As we do not have much information about the user, we'll simply ask a user about his gender. If an email cookie exists and matches, then a prompt will ask a user to confirm his gender. If gender-matched with the cookie, then a password will be shown to the user, if a user selects the wrong gender, then it'll be assumed that the user is a bad guy, and all the data from the cookie will be destroyed.


--> Destroy Session:-
Destroy session can be found on a profile page, after clicking on that button, all the data from the cookie will be destroyed and that will redirect the user to the registration page to start from scratch.
