# How to use CMU EntraID with Next.js 15

The repo shows how to implement CMU EntraID (sign-in with CMU Account) in your own web app using Next.js + TypeScript. We get CMU basic info (like student name, student id,..) after signing in then we use this information to create our own session.

[More information about CMU EntraID](https://docs.google.com/document/d/1E4NURlMTZrbzK-42LH6o5o4LfbPdLd2us87wK10vdIc/edit?usp=sharing)

## Please do the following steps before you start

1. Run `npm install` command in your terminal.
2. Copy `env.template` to `.env` file
3. Edit the following variables in the `.env` file accordingly.
   - `CLIENT ID`
   - `CLIENT SECRET`
   - `CMU_ENTRAID_REDIRECT_URL`
5. Run `npm run dev` command in your terminal.

## Warning

Do not push `.env` file to any git repositories. You should not include `.env` in repository at all!
