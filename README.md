# Money Buddy - Front-End

Front-end code of Money Buddy.

## Technologies

- React

## How to Develop

```
npm install
npm start
```

Please note that you'll also need to have an instance of the [back-end](https://github.com/samuelgrigolato/moneybuddy) up and running before opening the web application.

## How to Build for Production

```
npm run build
```

## How to Deploy

This project has everything needed to be deployed on Heroku (see the `Procfile`). Note that you'll need to set up a multi-buildpack configuration on your Heroku application before pushing code. You can do that this way:

```
heroku buildpacks:set heroku/nodejs
heroku buildpacks:set --index=2 https://github.com/heroku/heroku-buildpack-static.git
```

Note that the commands above will only work if you are under a Git repository that has the Heroku remote correctly configured. You can add a Heroku remote to an existing repository using the following command:

```
heroku git:remote -a <heroku-app-name>
```
