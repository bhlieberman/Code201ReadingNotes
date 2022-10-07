# OAuth

1. OAuth is an authorization standard on the web. It is used by web apps to provide a common interface for authenticating users.
2. Any web app that lets you log in with Google or Facebook etc is using OAuth.
3. OAuth works by two sites (the one asking for authorization and the other issuing it) exchanging the user's data and tokens that correspond to a verified user.
4. OpenID predates OAuth but was for authentication instead of authorization. 

# Authorization flows

1. Authentication is for "humans logging into machines," by comparison to authorization, which is "machines logging into machines on behalf of humans."
2. It is the process by which web apps use secrets to authorize a user.
3. A web app generates a code verifier and challenge that is sent to the endpoint that verifies these secrets and issues a token authorizing the user.
4. Implicit forms are no longer recommended for use but they allow a user to authenticate via a traditional post form.
5. It is used for CLIs and server daemons that don't support user input for authentication.
6. It is used for two-factor authentication on devices that don't easily support text input.
7. It asks the user for their username and password but this is not recommended because the credentials are stored in the application. If the app isn't highly trusted, this is insecure.


