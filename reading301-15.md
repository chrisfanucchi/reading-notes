# Reading: Class 15 - Authentication

## What is OAuth

1. What is OAuth?

   It is an open-standard authorization protocol for server and services to communicate more safely, without sharing login credentials.

2. Give an example of what using OAuth would look like.

   Such an authorization would come from a third party that is trusted by both communicating servers/services. The third party authentication authorizes the access without having to reveal the access requester's credentials.

3. How does OAuth work? What are the steps that it takes to authenticate the user?

   > - The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.
   > - The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
   > - The first site gives this token and secret to the initiating user’s client software.
   > - The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
   > - If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
   > - The user approves (or their software silently approves) a particular transaction type at the first website.
   > - The user is given an approved access token (notice it’s no longer a request token).
   > - The user gives the approved access token to the first website.
   > - The first website gives the access token to the second website as proof of authentication on behalf of the user.
   > - The second website lets the first website access their site on behalf of the user.
   > - The user sees a successfully completed transaction occurring.
   > - OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed (for various reasons). [^1]

4. What is OpenID?

   OpenID is a single sign-in ID for authenticating a user.

## Authorization and Authentication flows

1. What is the difference between authorization and authentication?

   Authorization grants access, while authentication confirms identity.

2. What is Authorization Code Flow?

   It is a server-side exchange of tokens between server's attempting to communicate, utilizing a trusted third party.

3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

   It is an authorization code flow with the added security of a verification at the App level.

4. What is Implicit Flow with Form Post?

   It is a simpler, less secure method of authorization that can use OpenID to facilitate the authorization. This method can be used with public-facing apps, where it isn't possible to store "client secrets."

5. What is Client Credentials Flow?

   This method of security is when the app is authenticated/authorized, rather than the user.

6. What is Device Authorization Flow?

   This method allows a user to authenticate via a user-friendly device, when having to deal with getting a input-restricted device connected to a server/service (like an Amazon Echo connecting to the Internet through configuration on a smartphone app).

7. What is Resource Owner Password Flow?

   This method forwards a user's login name and password to the Auth0 server, putting the user's login information at risk of compromise.

## Things I want to know more about

I can't wait to put Auth0 into action!

---

[^1]: _What is OAuth? How the open authorization framework works_, Retrieved on October 6, 2022, from [https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)
