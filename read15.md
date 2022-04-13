# Read: Class 15-  What is OAuth)

[What is OAuth? How the open authorization framework works](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)

1.What is OAuth?
***OAuth*** (open-standard authorization) is what allows us to use our log in from another website to log into a new website

2.Give an example of what using OAuth would look like.

* A user going on a new site where they are asked to log in and using their gmail to access this site instead of creating a new site.

3.How does OAuth work? What are the steps that it takes to authenticate the user?

* `"The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.`

* `The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.`
* `The first site gives this token and secret to the initiating user’s client software.`
* `The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).`
* `If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.`
* `The user approves (or their software silently approves) a particular transaction type at the first website.`
* `The user is given an approved access token (notice it’s no longer a request token).`
* `The user gives the approved access token to the first website.`
* `The first website gives the access token to the second website as proof of authentication on behalf of the user.`
* `The second website lets the first website access their site on behalf of the user.`
* `The user sees a successfully completed transaction occurring.`" - (<https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html>)

4.What is OpenID?

* OpenID is used for authentication

[Authentication and Authorization Flows](https://auth0.com/docs/get-started/authentication-and-authorization-flow)

1. What is the difference between authorization and authentication?

* Authenication uses OpenID

2.What is Authorization Code Flow?

* Authorization Code Flow is what exchanges an authorization code for a token

3.What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

* PKCE is what helps mitigate additonal security on apps as well as other challenges

4.What is Implicit Flow with Form Post?

* It is for public apps that are not able to securely store client secrets. (this is not the best practice)

5.What is Client Credentials Flow?

* Client credentials flow authenticates and authorizes the app instead of the user

6.What is Device Authorization Flow?

* The devices gives the user a link to click on and authorize

7.What is Resource Owner Password Flow?

* Requests the client to provide their password and username
