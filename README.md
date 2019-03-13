# Simple JWT Application

[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

A sample JWT web app that can be use to demonstrate how JWT tokens work. You can break down the JWT Token at [JWT.io](https://jwt.io/)'s debugger tool.


## How to run it

  1. Clone this repo
  2. Install dependencies `npm install`
  3. Run the server `npm start`
  4. See the magic at: [localhost:8000](http://localhost:8000)

## Configuration

The app can be configured through environment variables before running the server.

The configuration variables available are:

  - `USERNAME`: the username accepted for login (default `albert`)
  - `PASSWORD`: the password to pass for the login (default `einstein`)
  - `SECRET`: the secret used to sign the jwt token (default `secret`)



