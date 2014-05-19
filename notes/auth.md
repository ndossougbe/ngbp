### Auth process:

* https://github.com/enginous/angular-oauth
* custom:

```
Check cookie/localstorage.

if ! user authenticated:
    request login page
    display login page
    login page transmits data to server
    server redirects to the app and delivers an access token
end

use access token to request user info
```
