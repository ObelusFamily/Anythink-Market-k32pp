# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Start by cloning the repo to you local machine and create a new branch. Add the CODEOWNERS files given to you to that branch and do a pull request, after beeing approved go ahead and merge that branch with the main branch.
With the merge complete its time to create your own codespace with the help of the development environment that's hosted in the cloud called [Github Codespace](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=553060648) that was developed by the engineers at Anythink.

Now that your codespace is up and running its time to run "docker-compose up" in your codespace's terminal to load Anythink's backend and frontend.
Once docker-compose finishes loading up, the backend should be running and able to connect to the database.
After the server is up, make sure you test it by pointing your browser to https://obelusfamily-anythink-market-k32pp-jwv7pxgv9qp3q77x-3000.githubpreview.dev/api/ping
Now, it’s time to check the frontend and make sure it’s connected to the backend.
If everything is working properly, you’ll be able to create a new user on https://obelusfamily-anythink-market-k32pp-jwv7pxgv9qp3q77x-3001.githubpreview.dev/register

And you've completed your first setup of now