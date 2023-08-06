# AuthForm-EmailVerification-PHP
login &amp; signup form with email verification using PHP and sql with complmete validation
As we all know, the login and & Signup Form is the set of different input fields – Name, Email, Username, Password, etc. which are used to authenticate users before giving access to the site. In our program [log in & Signup Form with Email Verification], there are eleven PHP files and one is a CSS file means there are a total of twelve files in our user name folder.
At first, on the webpage, there is shown only a login form and inside the login form, there is a signup now link to redirect the user to the first signup before login. When the user tries to log in without even signup the form, there is displayed an error message labeled as “It looks like you’re not yet a member! Click on the bottom link to signup”.

In the signup form, while the user is signing up, if he enters the same email, which already exists in our database then there is displayed an error message labeled as “Email that you’ve entered is already exist!”. And when the user doesn’t match two password combinations, there is also displayed an error message labeled as “Your confirm password not matched”.

When the user filled up all the required inputs correctly, then a six-digit verification code number is sent to the user’s email and he will be redirected to the OTP Verification page. If the user entered the wrong code, there is displayed an error message labeled as “You’ve entered incorrect code!”. If the user exit the OTP verification code page without entered a valid or correct verification code and come to the login page to log in with the same email and password which he used to sign up, then he will be again redirected to the OTP page and there is displayed an info message labeled as “It looks like you’ve not verified your email”.
