# Multi factor authentication

### Instructions: to start this app

1. Inside the project folder install the required packages -

`$npm install`

2. Compile JavaScript modules

`$npm run build:dev`

3. Start the server

`$npm run server:dev`

4. On the browser the application gets launched - Server running on http://localhost:8080

5. Enter user name `jill` with password `2`, click Log in

6. Next page displays Verification code empty field

    - As we need to get the verification code thru terminal for now
    - Click on Confirm button 
    - Go to terminal of your application *server* 
    - Get the last code from console
    - Enter the *verification code* on the browser and click *Confirm* button

7. Once the *verification code* gets verified, displays a message with the user name

    ```
    Hello, jill. Logout

    Congratulations, multi factor authentication is enabled.
    ```

8. Click logout will take you to login screen
