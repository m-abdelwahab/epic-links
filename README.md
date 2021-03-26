# Getting Started

First, install dependencies and run the development server:

```bash
yarn && yarn dev
```


To set up the project locally you'll need to have a database, you can use [Heroku](https://dev.to/prisma/how-to-setup-a-free-postgresql-database-on-heroku-1dc1) or a local Postgres DB

You'll also need to have a GitHub app for auth, so just [create a new Oauth app](https://github.com/settings/applications/new) and make the authorizationn callback URL : `http://localhost:3000/api/auth`

create a `.env` file 


```
DATABASE_URL = 
GITHUB_ID = 
GITHUB_SECRET = 
NEXTAUTH_URL = http://localhost:3000
JWT_SECRET = superrandomLongSecretThaTIsHardToGuess

```