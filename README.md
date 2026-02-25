=======
# Sanity Studio For the PEDP Website

This repo contains the code for the backend CMS studio (Sanity) for the new PEDP website.

## Setup

First, clone the repo locally.

Install the dependencies:

	npm install

Set up your local `.env` file. Copy the `.env.example` file and update it with the correct values.

Then in the project directory, run

    npm run dev

Now you can log in to the Studio:

Open the Studio running locally in your browser from http://localhost:3333.

You should now see a screen prompting you to log in to the Studio. Use the same service (Google, GitHub, or email) that you used when you logged in to the CLI.

## Deploy your changes

Deploy your changes to the hosted Sanity studio so that content managers can use them!

	npm run deploy
