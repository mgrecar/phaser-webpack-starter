# Overview

This repo is just a quick and simple starter for use as a project template for developing games using [Phaser](http://www.phaser.io) with [Webpack](http://webpack.github.io).

I found that after following along with a few Phaser tutorials, and struggling with getting everything to build correctly twice under Webpack, it would be smart to store a slim, minimal setup that I could just clone and get started with.

## Prerequisites:
1. Node.js
2. Existing Heroku account
3. Heroku toolbelt installed

## Directions:
1. Clone this repo to a new project directory.
2. Run `npm install` in that directory.
3. Run `npm start` to start a webpack dev server.
4. Navigate to `localhost:3000` in a web browser to see the game.
5. Run `heroku create` to set up Heroku app with the project
6. Run `git push heroku master` to deploy the master branch to Heroku
7. Run `heroku open` to check that everything deployed successfully.


## Further Details

Most of the details to actually get it running came out of the [Phaser README](https://github.com/photonstorm/phaser#webpack-config), but I found I had to do a little tweaking to get a full setup actually working.
