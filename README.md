# usermanagement-node

## Goal
The goal of this module is to provide Identity and user-management APIs for mobile and web applications. This let's developers to focus on the core app therby allowing to ship applications faster.

### Features
- CRUD operations for users
- Authentication
- CRUD for roles
- Assignment of priviliges to roles
- Assignment of role to users

## Setup
This application can be independently deployed.
Follow the below instructions.

<--- Add installation steps -->

## API Doc
Once installed and running the API doc can be accessed at `http://<host:port>/apidoc/`. The document is also availaible at `http://oodebe.com:7000/user-management/apidoc/`

## Limitations
The project is in active development phase. Currently it only supports simple email/password authentication using JWTs. See todos for more info.

## Todos
- Add multiple auth strategies. (Google, Facebook)
- Ability to be used by multiple applications from a single instance.
- Delete API for roles
