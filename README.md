# PASO -- "Paris Aeroport Site refont"

## INSTALL

1. Pre-requisites: Install PostgreSQL

Navigate to `https://www.postgresqltutorial.com/postgresql-getting-started/install-postgresql/` 


2. Create your `adp_paso` database:

```sh
$ psql -U $USER
postgres=# CREATE DATABASE adp_paso;
postgres=# quit
```

## How To Get Started With The Project


1. Run `setup` command to setup frontend and backend dependencies:

```bash
  yarn setup
```

2. Next, navigate to your `/frontend` directory and set up your `.env` file. You can use the `.env.local.example` file as reference:

3. Next, navigate to your `/frontend` and start your project by running the following command:

```bash
  yarn build
```

4. Next, navigate to your `/backend` directory and set up your `.env` file. You can use the `.env.example` file as reference:

5. Next, navigate to your `/backend` and start your project by running the following command:

```bash
  yarn build
```


## Starting Both Projects

You can start each project individually, by running the following commands.

In your terminal, change directory to `backend` and run `yarn develop`, then in a new terminal window, change directory to `frontend` and run `yarn dev`.

You can also run both projects using **concurrently* to start both projects by running `yarn dev` in the root of your project.

Navigate to `http://localhost:3000` and should see the following screen.
You can find your Strapi app running on `http://localhost:1337`.