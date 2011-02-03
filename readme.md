Early alpha, please use with caution!

brunch is an opinionated client side framework on top of backbone.js, eco and stylus using coffee-script

## How to Install

you can get brunch using the node package manager

    npm install brunch

## How to Use

create a new project using 'proj' as app namespace

    brunch new <proj>

start the file watcher to process all .coffee, .sass or .html file changes automatically

    brunch watch

build the project

    brunch build

brunch provides the possibility to choose between different project templates
currently these are available

* express (default)
* base

you can choose between them via option "--projectTemplate"

    brunch new my_app --projectTemplate base

## project templates

### base

Just the basic brunch layout including src, config and build.

### express

Includes build in express server which will be started with "brunch watch".
You can take a look at the app at "localhost:8080".

## Standing on the Shoulders of Giants

Instead of reinventing the wheel, brunch assembles awesome wheels.

* [CoffeeScript](http://jashkenas.github.com/coffee-script/)
* [Backbone](http://documentcloud.github.com/backbone/)
* [Underscore](http://documentcloud.github.com/underscore/)
* [jQuery](http://jquery.com/) or [Zepto](http://zeptojs.com/)
* [Stylus](https://github.com/LearnBoost/stylus)
* [Eco](https://github.com/sstephenson/eco)

## TODO

* more & improved documentation
* copy js files from src to build
* move watch to own node package or at least to another file
* proper error message if brunch directory already exists
* proper output info
* tests
* impove childspawn - see http://nodejs.org/docs/v0.3.7/api/child_processes.html#child_process.spawn

### other stuff

* add twitter account
* register irc channel
* add zepto to brunch cdn

## Future plans

* add vendor scripts for development
* add "build deploy" which generates index.html with script tags using cdn
* add phonegap support
