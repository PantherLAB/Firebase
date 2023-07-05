# firebase-api

## How to create  a firebase project:

1. go to https://firebase.google.com/
2. Click  the button  "Get Started"
3. Click  the button "Add Project"
4. Add a project  Name
5. Disable "Enable Google Analytics for this project" and click "Create project"
6. Create new Real Time Database <br><img src="assets/realTimeDB.png" width="40%" height="40%">
7. Click  The Button  "Create Database"
8. Select the desired Location and click "Next"
9. Select Test Mode and click Enable <br><img src="assets/testMode.png" width="50%" height="50%">
10. Locate the DB URL and the rules editor This is the "Firebase URL" to be used by the API <br><img src="assets/databaseURL.png" width="50%" height="50%">

## How to enable Authentication:

1. Select Authentication and click "Get Started" <br><img src="assets/authentication.png" width="50%" height="50%">
2. Select Sign-in method tab and click the "Email/Password" Button <br><img src="assets/SignInProviders.png" width="50%" height="50%">
3. Click the Enable "Email/Password" Checkbox and click the "Save" Button
4. Go to the Project Overview (click the gear button) and select "Project Settings", find the Web "API_Key" <br><img src="assets/webAPIkey.png" width="50%" height="50%">


## Using Firebase API

### Autenticate a new User

Open Sign In Example.vi and update the "API_KEY" and "Firebase URL" with the ones obtained in the previous steps <br><img src="assets/SignUPFirebase.png" width="50%" height="50%">

This Example will add your USER to the autenticated Users list <br><img src="assets/AutenticatedUserList.png" width="50%" height="50%">

### Post to Real Time DB

Open Log in and Post.vi Example, use your "API_KEY", "Firebase URL" and your Authenticated user to POST something to your Real Time Database, in this example we published a cluster called data, data is the endPoint name <br><img src="assets/logInPost.png" width="50%" height="50%">

