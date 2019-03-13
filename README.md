# Simple JWT Application

[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

A sample JWT web app that can be use to demonstrate how JWT tokens work

## Idea

This is a simple application where you can login as a user with normal privileges (so normal that you can't do anything!) and by hacking the session id (which is a simple JWT) you should try to escalate your privileges to being an admin.

## How to run it

  1. Clone this repo
  2. Install dependencies `npm install`
  3. Run the server `npm start`
  4. See the magic at: [localhost:3000](http://localhost:3000)

## Configuration

The app can be configured through environment variables before running the server.

The configuration variables available are:

  - `USERNAME`: the username accepted for login (default `albert`)
  - `PASSWORD`: the password to pass for the login (default `einstein`)
  - `SECRET`: the secret used to sign the jwt token (default `secret`)



