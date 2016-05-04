The `apiapp` endpoint allows users to define an alternate authentication mechanism.

The App token interface is used primarily for integrations you hand off to another team or 3rd party developer, where you’d rather give them a revokable token for authentication rather than sending your password with the request.  

The main benefits being:

1.   You can revoke access later from your account, without having to change your password.
1.   You’re not giving your developer access to log into the site, just to use the API.

If you're the site user, and you’re doing all the integration work yourself, it’s probably fine to just use your password for authentication.

#### Permissions

Permissions in the API are based on the user-permissions assigned to the username you are using to access the API.  These can be configured from the Portal website.  The API Apps are no exception, each app token is tied to a specific user, and you can set permissions and vehicle access directly on that username from the Portal site.  There are no additional permissions or roles assigned to App Tokens outside of user permissions.
