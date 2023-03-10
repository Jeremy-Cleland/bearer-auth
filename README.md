# LAB - Class 07 Bearer Auth

## Project: bearer-auth

### Author: Jeremy Cleland

### Problem Domain

Construct a server that allows the user to create an account as well as to handle Basic Authentication (the user provides a username + password). When a “good” login happens, the user is considered to be “authenticated” and our auth-server generates a JWT signed “Token” which is returned to the application. Using that Token to re-authenticate users we will shield access to any route that requires a valid login to access.

### Links and Resources

- [GitHub Actions ci/cd](https://github.com/jeremy-cleland/bearer-auth/actions)
- [GitHub PR](https://github.com/jeremy-cleland/bearer-auth/pull/1)
- [back-end server url](https://bearer-auth-arnl.onrender.com)

### Setup

#### `.env` requirements (where applicable)

```
PORT=3001
DATABASE_URL=postgres://localhost:5432/bearer-auth
SECRET=<Some secret string>
```

#### How to initialize/run your application (where applicable)

- e.g. `npm start`

#### How to use your library (where applicable)

#### Features / Routes

- Feature 1: Fixed Bugs
  - Used testing to troubleshoot bugs and errors

- Feature 2: secure the JWT Tokens
  - Add support for the creation and usage of time-sensitive (valid for 15 minutes) JWTs

#### Tests

Tests were provided with the starter code

#### UML

[From Class 07 UML](https://projects.invisionapp.com/freehand/document/DkHU4YFRY)

![Class 07 UML](/assets/lab07_uml.png)
