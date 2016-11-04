# Simple-Form
###This is just a simple Sign Up, Sign In, and Forgot Password Form.
###This form could simulate a login, sign up, and resetting password.
###I used localstorage to save some user data.
###The Sign Up form will add those data into an array of object in javascript and it will be added into the localstorage (as strings - using stringify).
###In the Sign In form, user insert their recorded email and password. After that data from the localstorage will be retrieved and will be parsed into JSON object. If there is a matched data, then an alert will pop out and welcoming the user. When the remember me checkbox is checked, then when the user navigated to the signup.html, an alert will also pop up stating that there is an active user. (when the rememberme checkbox is checked, the data are also saved inside the localstorage as string and retrieved the same way using JSON parse).
###The Forgot password form checks the data availability inside the localstorage and if there is a match, then the password is reset to "joe".
###the reset button bellow the sign up button in the signup.html is used to clear the localstorage.
