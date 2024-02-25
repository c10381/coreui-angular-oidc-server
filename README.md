# OIDC Server integration with Coreui angular demo
This is an example of how to integrate the angular-oidc-server library with CoreUI Template for Angular version using Code Flow Authentication.

## Point
1. entry point: `AppConponent:constructor`
2. Main ts: `auth.service.ts`
3. Config ts: `auth-code-flow.config.ts`
4. Authentication flow is `Authorization Code Flow with Proof Key for Code Exchange (PKCE)`，And with `refresh token`
5. [authorization-code-flow-with-pkce#request-tokens implementation by Auth0](https://auth0.com/docs/get-started/authentication-and-authorization-flow/authorization-code-flow-with-pkce/call-your-api-using-the-authorization-code-flow-with-pkce#request-tokens)
