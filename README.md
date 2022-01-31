<!--- STARTEXCLUDE --->

# Build an Astra DB RPG

_30 minutes, Advanced, [Start Building](https://github.com/DataStax-Examples/rpg-astra/blob/master/README.md#quick-start)_

This example is a simple RPG application that allows you to add skills and allocate skill points to them, gaining you experience and levels as a result.

<!--- ENDEXCLUDE --->

![image](https://raw.githubusercontent.com/DataStax-Examples/rpg-astra/master/hero.jpg)

## Quick Start

<!--- STARTEXCLUDE --->
- [Signup for DataStax Astra](https://astra.dev/3ANTraE), or login to your already existing account.
- [Create an Astra DB Database](https://github.com/DataStax-Examples/sample-app-template/blob/master/GETTING_STARTED.md#create-an-astra-db) if you don't already have one.
<!--- ENDEXCLUDE --->
- [Create an Astra DB Keyspace](https://github.com/DataStax-Examples/sample-app-template/blob/master/GETTING_STARTED.md#create-an-astra-db-keyspace) called `sag_rpg` in your database.
- [Generate an Application Token](https://github.com/DataStax-Examples/sample-app-template/blob/master/GETTING_STARTED.md#create-an-application-token) with the role of `Database Administrator` for the Organization that your Astra DB is in.
- Click the 'Open in Gitpod' link: [![Open in IDE](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/DataStax-Examples/rpg-astra)
- Once the app is finished launching in the Gitpod IDE, copy the `env.example` file to a file named `.env` and fill the required values in from your Application Token and [Astra DB connection settings](https://github.com/DataStax-Examples/sample-app-template/blob/master/GETTING_STARTED.md#get-your-astra-db-connection-settings).
- Start the example by running `npm run dev` in the Gitpod console.

## Objectives

Launch and explore an example of a RPG app in [Gitpod](https://www.gitpod.io/), built with [React](https://reactjs.org/) and [Netlify](https://www.netlify.com).
