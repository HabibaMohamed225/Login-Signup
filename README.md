This is a simple mobile app built using Flutter, which contains two main screens:
Login Page (MyHomePage)
Sign Up Page  (SignUpPage)

The user can navigate between them using buttons.

Screens Details
Login Page
Contains:
Title: Welcome Back
Two text fields: username and password.
A login button.
A clickable text: "Sign Up" to navigate to the Sign Up screen.

Sign Up Page
Contains:
Title: Sign up
Four text fields: username, email, password, confirm password.
A sign-up button.
A clickable text: "Login" to go back to the Login screen.

Navigation
We used Navigator.push()and MaterialPageRoute to switch between screens.
The Sign Up button on the Login screen navigates to SignUpPage.
The Login text on the Sign Up screen navigates to MyHomePage.

dart
Navigator.push(
  context,
  MaterialPageRoute(builder: (context) => SignUpPage(title: '')),
);
