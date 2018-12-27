# Project Plus Slides Starter Template

This starter template contains an index.html which links to a local, non-minified D3.js.
If it's working properly, it will show a "Hello World" page locally using `grunt serve` and on Github Pages once you change your repository settings.

I built the following starter template for myself with two objectives:

## Quickly spin up a repository that used `grunt serve`

This repository supports the Grunt task runner. After following the instructions in
Setup, you can run `grunt serve` at the command line in the root directory
of your project and see your site at localhost:9000.

## Have a repository that published cleanly to Github Pages

As-is, once you add files to your repository, you should be able to push it to
Github and see the results on Github Pages.  Once you've pushed, you'll need to
go to Settings > Github Pages and tell Github which branch should publish a Github Pages site for you. The .gitignore ignores environmental variables and node_modules.

## Have a repository where a folder could contain a web presentation deck

The /slides folder contains a basic template for a web-ready presentation slideshow using reveal.js.

## Setup

Fork and clone this repository.

Once you have it in a local directory, you can change its name.

At the command line, run `npm install` in the root directory.

Run `grunt serve` and then check http://localhost:9000/index.html to see if you see a "Hello World!" page. If it is, you are up and running!

You must run `npm install` in the `slides` folder as well if you want to spin up a slide deck using reveal.js. That will also work with Grunt. 

Once you make any changes you want, push your changes and visit Settings to turn on Github Pages.
