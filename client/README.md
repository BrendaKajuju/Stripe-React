# Payment details

## How to run locally

Running a backend server is a requirement and a dependency for this React front-end to work. See the README in the root of the project for more details.

To run the React client locally:

1. Install dependencies

From this directory run:

```sh
npm install
```

2. Start the react app

```sh
npm start
```

or 

```sh
npm run start
```

This will start the react server running on localhost:4242. Note that the
backend server runs on localhost:5252, but the React frontend will be available at
localhost:4242. API requests to the backend are proxied by the
create-react-app server using the `proxy` setting in `./package.json`.
