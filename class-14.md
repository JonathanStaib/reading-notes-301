# Class 15 Reading Notes

## What is OAuth?

1. Auth0 is a way for servers and services to be accessed safely.

2. An example of OAuth could be You use google to log in and it authenticates you.

3. Steps OAuth takes: [Copied From Here](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)

    1. The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.
    2. The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
    3. The first site gives this token and secret to the initiating user’s client software.
    4. The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
    5. If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
    6. The user approves (or their software silently approves) a particular transaction type at the first website.
    7. The user is given an approved access token (notice it’s no longer a request token).
    8. The user gives the approved access token to the first website.
    9. The first website gives the access token to the second website as proof of authentication on behalf of the user.
    10. The second website lets the first website access their site on behalf of the user.
    11. The user sees a successfully completed transaction occurring.
    12. OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed (for various reasons).

4. OpenID is another force of security. OpenID is used for authentication rather than authorization like OAuth.

## Authorization and Authentication flows

[Resource Here](https://auth0.com/docs/get-started/authentication-and-authorization-flow)

1. Authentication is the process of verifying who a user is, while Authorization is the process of verifying what they have access to.

2. Authorization Code Flow trades an Authorization Code for a token.

3. PKCE is additional level of security for Authorization.

4. Implicit Flow with Form Post is intended for Public Clients. Alos, applications that are unable to securely store secrets.

5. Client Credential Flow is when the system authenticates or authorizes an ahpp rather than a client/user.

6. Device Authorization Flow is when the device asks you to go to anotehr link for authorization.

7. Resource Owner Password flow is when you require the user to enter username and password. Highest security but not reccomended.
