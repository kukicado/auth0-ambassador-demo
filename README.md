# Auth0 Ambassador Demo

This repo contains the code shown in the Auth0 Product training session. To get the project up and running follow these steps:

1. Sign up for an Auth0 account at https://auth0.com/signup
2. Create a New Client and copy its `ClientID`
3. Create a New API and copy its `Audience`
4. Edit the `.env` file with your `Auth0 Tenant Domain` and `Audience`
5. Edit the `auth0-variables.js` file with your `ClientID`, `Audience`, and `Auth0 Tenant Domain`
6. Install Node dependencies by running `npm install`
7. Start the server by running the `npm start` command
8. Ensure that `localhost:5000` is in your list of **Allowed Callback URL's in the Auth0 Dashboard for the Client Created**
9. Ensure that the API you created has a `read:messages` scope added

Your API will run on `localhost:3001`, while your UI will run on `localhost:5000`.

From here you should be able to make any changes in the Auth0 Dashboard and see them reflected in your application when you attempt to login. Happy hacking!

