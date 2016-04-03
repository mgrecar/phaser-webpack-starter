# Overview

This repo is just a quick and simple starter for use as a project template for developing games using [Phaser](http://www.phaser.io) with [Webpack](http://webpack.github.io).

I found that after following along with a few Phaser tutorials, and struggling with getting everything to build correctly twice under Webpack, it would be smart to store a slim, minimal setup that I could just clone and get started with.

This project is designed to be a starter template, from which you clone and separate to a new origin for your own projects.  The intent is you have a basic Phaser game project that can immediately be deployed to Heroku for fast iteration.

All directions are written from a Linux perspective.  While they should basically work with Mac OS X, there might be adjustments, and Windows most assuredly needs some translation.

Directions for uploading your new project to Github can be found [here](https://help.github.com/articles/create-a-repo/), and deploying the new project to Heroku can be found [here](https://devcenter.heroku.com/articles/getting-started-with-nodejs#deploy-the-app).

## Prerequisites:
1. Node.js with NPM
2. An existing Heroku account
3. The Heroku toolbelt

## Installation:
1. `git clone git@github.com:mgrecar/phaser-webpack-starter.git <new_project_name>`
2. `cd <new_project_name>`  
3. `npm install`
4. `git remote rm origin`

Now, you have a completely independent local project to start development with.

## Local Development:
1. `npm start`
2. Navigate to `localhost:3000`
3. Iterate, develop and commit your new project.  Hot Module reloading should be in place view webpack-dev-server.

## Further Details

Most of the details to actually get Phaser running with Webpack came out of the [Phaser README](https://github.com/photonstorm/phaser#webpack-config), but I found I had to do a little tweaking to get a full setup actually working.  Details for adjusting the setup to work more cleanly and for Heroku production/development separation were assisted by [The ultimate Webpack setup](http://www.christianalfoni.com/articles/2015_04_19_The-ultimate-webpack-setup).
