## How to Run

### Run server permenantly
> npm run dev

### Run client
> npm run start:app   //  npm run start

Navigate to http://localhost:3000 

## Main modules

## Main libraries

### Authentication for some of your favorite socials including Facebook, Instagram, Google, Twitch, Github, and Amazon!

Open [http://www.passportjs.org](http://www.passportjs.org) to see about passport auth strategies.

We are using `passport`, `passport-facebook`, `passport-google-oauth20`, `passport-instagram`, `passport-twitch`, `passport-github` npm libraries for those social auth.
```
npm i -S express passport passport-facebook passport-google-oauth20 chalk
```

1. `chalk` module is for the purpose of coloring console logs.
Check this for detailed api.
[https://www.npmjs.com/package/chalk](https://www.npmjs.com/package/chalk)

2. Run command `pm2 ecosystem` to generate default ecosustem.config.js file

3. `http-proxy-middleware` is going to run client and servr at same port 3000.
    To be honesty, api request `/auth` will be redirect to port 5000 automatically through middleware.

4. `concurrently` is going to run client and server script at the same time, concurrently.


