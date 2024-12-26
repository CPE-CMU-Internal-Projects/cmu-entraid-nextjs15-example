# How to use CMU EntraID with Next.js 15

The repo shows how to implement CMU EntraID (sign-in with CMU Account) in your own web app using Next.js + TypeScript. We get CMU basic info (like student name, student id,..) after signing in then we use this information to create our own session.

[More information about CMU EntraID]()

## Please do the following steps before you start

1. Run `npm install` command in your terminal.
2. Copy `env.template` to `.env` file
3. Edit your `CLIENT ID` and `CLIENT SECRET` in the `.env` file.
4. Run `npm run dev` command in your terminal.

## Warning

This repo include .env file to kickstart required variables for you. But in practice, you should not include .env in repository at all!
