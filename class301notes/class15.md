# OAuth ReadMe

## Reading: What is OAuth

### What is OAuth?

OAuth (Open Authorization) is an open-standard authorization protocol that allows third-party applications to access user data without exposing their credentials. It is widely used for enabling secure access to resources via APIs.

#### Give an example of what using OAuth would look like.

An example of using OAuth is when a user logs into a website using their Google credentials. The website requests access to certain user data (with user consent), and Google, acting as the OAuth provider, authenticates the user and grants the website limited access.

#### How does OAuth work? What are the steps that it takes to authenticate the user?

1. **User Authorization:** The user grants permission to a client application to access their resources.
2. **Authorization Server:** The client obtains authorization from the authorization server.
3. **Token Request:** The client requests an access token from the authorization server by presenting authentication of its own identity.
4. **Token Response:** If valid, the authorization server issues an access token.
5. **Access Resources:** The client accesses the protected resources using the access token.

#### What is OpenID?

OpenID is an authentication protocol built on top of OAuth that allows users to be authenticated on different websites without needing to create a new password for each.

### Authorization and Authentication flows

#### What is the difference between authorization and authentication?

Authentication is the process of verifying the identity of a user, while authorization is the process of granting or denying access to specific resources.

#### What is Authorization Code Flow?

Authorization Code Flow is an OAuth flow where the client application receives an authorization code, which is then exchanged for an access token.

#### What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

PKCE is an extension to Authorization Code Flow that adds an additional security layer, especially useful in mobile and native applications.

#### What is Implicit Flow with Form Post?

Implicit Flow with Form Post is a simplified OAuth flow for browser-based applications where tokens are returned directly in the URL fragment.

#### What is Client Credentials Flow?

Client Credentials Flow is an OAuth flow where the client uses its own credentials to authenticate and obtain an access token.

#### What is Device Authorization Flow?

Device Authorization Flow is designed for devices with limited input capabilities, allowing them to obtain user consent for authorization.

#### What is Resource Owner Password Flow?

Resource Owner Password Flow allows the client to directly obtain user credentials (username and password) and use them to obtain an access token.

## Things I Want to Know More About

- Real-world implementation scenarios for OAuth in different types of applications.
- Best practices for securing OAuth implementations and preventing common vulnerabilities.
- Advanced topics related to identity and access management.
