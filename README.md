# Secrets

- HTML
- CSS
- Bootstrap
- Node
- Mongo
- Hash

## Getting Started

- Make sure that you have MongoDB installed and running

```bash
mongod
```

- Install all the dependencies:

```bash
npm install
```

- Then run node:

```bash
node app.js --watch or nodemon app.js
```

## Some Information

- This web application uses a Google Cloud API, If you have some problems with the app, here's the documentation of Passport.js with the steps I followed:

```bash
https://www.passportjs.org/packages/passport-google-oauth20/
```

- Also, you will need to use your own .env file for some variables to be able to work, for example:

```bash
clientID: process.env.CLIENT_ID,
clientSecret: process.env.CLIENT_SECRET,
callbackURL: process.env.CALLBACK_URL,

--> Line 55
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
