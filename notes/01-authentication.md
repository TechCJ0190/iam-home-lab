Created Auth0 SPA app, set callback to http://localhost:3000, successfully authenticated via GitHub and was redirected (connection refused expected).
![First login](../screenshotsauth001-first-login.png)

Enabled Authenticator App MFA in Auth0 (Security → Multi-factor Auth).  
Second login required TOTP code from authenticator app; code accepted and redirected to localhost:3000 (connection refused expected).
