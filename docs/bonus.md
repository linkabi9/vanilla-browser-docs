# Bonus Section!

So you've finished the workshop before everyone else, or you're looking for some more challenging peices to work on? You've come to the right section!

The following are some sections that will provide the beginnings to some self-guided learning experiences that build on the skills we've learned in this workshop.

## Test with Mocha

## Heroku to Publish

[Heroku][heroku] is a web hosting platform that allows developers to go from code to running apps in minutes. It has a free tier, as well as a super fast workflow. To try it out create a free account on Heroku, and then use the button below to automatically deploy this app directly from GitHub to a running Heroku instance.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/sandiegojs/vanilla-browser-workshop)

Read [Getting Started with Node.js on Heroku][node-heroku] for more information.

## ES2015

You'll probably remember that the boilerplate for this workshop was setup with [Gulp][gulp]. If you take a peak at the `tasks/` directory at the `scripts` task and see how the scripts are being built you will notice the use of [Browserify][browserify] and the 'babelify' tranform which uses [Babel][babel].

Babel allows us to use ES2015 in the browser. There are many different plugins and presets you can add to the project's Babel configuration in `.babelrc`. The default [es2015][babel-es2015] preset should get you pretty far, but it would be useful to read up more information about Babel presets and plugins. Adding different plugins allows you to add more natively unsupported future features of EcmaScript.

Browserify allows us to use modules in our project. With the combination of Browserify and Bable we are able to have a great module ecosystem and ES2015.

One bonus skill of this workshop is moving the functionality of this app into composable modules. This will also allow us to add isolated unit testing to our test suite, rather than just integration tests.

Give this a try on your own!

## Fork the API and expand

The API for this project was build using [Rails-API][rail-api] and is publicly available for forking and PRs at [sandiegojs/sandiegojs-vanilla-workshop][sdjs-api]. Rails-API is similar to rails, except that it is API only. It doesn't include the view layer and other pieces that are unnecessary for creating an API.

If you want to expand on this example, you can try generating additional models and controllers in the API and adding more routes to your client-side application.

## Image uploading

## Push state

[babel]: http://babeljs.io
[babel-es2015]: https://babeljs.io/docs/plugins/preset-es2015/
[browserify]: http://browserify.org/
[gulp]: http://gulpjs.com/
[heroku]: http://heroku.com
[json-api]: http://jsonapi.org/
[rails-api]: https://github.com/rails-api/rails-api
[sdjs-api]: http://github.com/sandiegojs/sandiegojs-vanilla-workshop