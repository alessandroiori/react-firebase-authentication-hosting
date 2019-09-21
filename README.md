# React with Firebase Hosting, Firebase Auth and Firebase Realtime Database
How to deploy a React application to Firebase Hosting, authenticate with Firebase Auth and manage users with Firebase Realtime Database

### Sign In Page
![Sign In](https://github.com/alessandroiori/react-firebase-hosting-auth-realtimedb/blob/master/readme_img/1.png)

### Sign Up Page
![Sign Up](https://github.com/alessandroiori/react-firebase-hosting-auth-realtimedb/blob/master/readme_img/2.png)

### Home Page
![Home](https://github.com/alessandroiori/react-firebase-hosting-auth-realtimedb/blob/master/readme_img/3.png)

### Account Page
![Account](https://github.com/alessandroiori/react-firebase-hosting-auth-realtimedb/blob/master/readme_img/4.png)

### Admin Page
![Admin](https://github.com/alessandroiori/react-firebase-hosting-auth-realtimedb/blob/master/readme_img/5.png)

### Firebase Authentication
![Firebase Authentication](https://github.com/alessandroiori/react-firebase-hosting-auth-realtimedb/blob/master/readme_img/6.png)

### Firebase Database
![Firebase Realtime Database](https://github.com/alessandroiori/react-firebase-hosting-auth-realtimedb/blob/master/readme_img/7.png)

### Password Forget Page
![Password Forget](https://github.com/alessandroiori/react-firebase-hosting-auth-realtimedb/blob/master/readme_img/8.png)

### Reset Password from email
![Reset Password](https://github.com/alessandroiori/react-firebase-hosting-auth-realtimedb/blob/master/readme_img/9.png)

# Before run
Define the project environmental variables in a new .env file in your project’s root folder. The .env file was added to .gitignore file. Copying the configuration from your Firebase project’s dashboard. The .env file content:

```
NODE_ENV=production

REACT_APP_PROD_API_KEY=AAAAAAAAAAAAAAAAAAA
REACT_APP_PROD_AUTH_DOMAIN=AAAAAAAAAAAAAAAA.firebaseapp.com
REACT_APP_PROD_DATABASE_URL=https://AAAAAAAAAAAAAAAA.firebaseio.com
REACT_APP_PROD_PROJECT_ID=AAAAAAAAAAAAAAAA
REACT_APP_PROD_STORAGE_BUCKET=
REACT_APP_PROD_MESSAGING_SENDER_ID=AAAAAAAAAAAAAAAA
REACT_APP_PROD_APP_ID=A:AAAAAAAAAAAAAAAA:web:AAAAAAAAAAAAAAAA
REACT_APP_PROD_CONFIRMATION_EMAIL_REDIRECT=https://AAAAAAAAAAAAAAAA.firebaseapp.com/


REACT_APP_DEV_API_KEY=AAAAAAAAAAAAAAAA
REACT_APP_DEV_AUTH_DOMAIN=AAAAAAAAAAAAAAAA.firebaseapp.com
REACT_APP_DEV_DATABASE_URL=https://AAAAAAAAAAAAAAAA.firebaseio.com
REACT_APP_DEV_PROJECT_ID=AAAAAAAAAAAAAAAA
REACT_APP_DEV_STORAGE_BUCKET=
REACT_APP_DEV_MESSAGING_SENDER_ID=AAAAAAAAAAAAAAAA
REACT_APP_DEV_APP_ID=1:AAAAAAAAAAAAAAAA:web:AAAAAAAAAAAAAAAA
REACT_APP_DEV_CONFIRMATION_EMAIL_REDIRECT=http://localhost:3000
```

## Run
In the project directory, run:

[Local test]
#### `npm start`

[Firebase deploy]
#### `npm run build; firebase deploy`

## Sources
- [A Firebase in React Tutorial for Beginners [2019]](https://www.robinwieruch.de/complete-firebase-authentication-react-tutorial)
- [How to deploy a React application to Firebase](https://www.robinwieruch.de/firebase-deploy-react-js)
- [The Road to React with Firebase (book)](https://github.com/alessandroiori/react-firebase-hosting-auth-realtimedb/blob/master/the-road-to-react-with-firebase.pdf)
