# DH Recipes

Community contributed recipes and techniques for Digitial Humanities

# How can I help?
Have a recipe or tutorial for the Digital Humanities? Awesome, this is
the place to go if you're looking to contribute.

Once you have [forked the project][github-forking], send a [pull
request][github-pull-requests]. Please be sure to follow the [style
guidelines][style-guidelines].

You can also get in touch with us on [irc][irc].

Need a prompt? Check out the [issue tracker][issues] for recipes that
have been requested, or are in progress. 

## Here's the rundown

To get started, you should clone the repository from github:

    git clone git://github.com/waynegraham/dh-recipes.git

Once you `cd` in to `dh-recipes`, you should see the
[Sinatra][sinatra] files. There are several that you should be aware of:

    app.rb    # a tiny application for displaying the contributed recipes
    confug.ru # rackup file for deploying the application
    Gemfile   # dependencies file for bundler to run the app

If you want to run the application yourself, you will need the `bundler`
gem:

    gem install bundler

Once bundler is installed, you only need to run `rackup` in the
application root and visit: [localhost:9292](http://localhost:9292).

This application just maps flat files, so you can either browse the
source or use the web application to view the recipes.

If you look at the source, you will see a few directories listed. In
each directory, there is a `README.md` that briefly describes the topic.
This can also be viewed by visiting `/p/:topic` where `topic` is the
directory you wish to view. 



[sinatra]: http://www.sinatra.com/
[issues]: http://github.com/waynegraham/dh-recipes/issues/
[style-guidelines]: http://github.com/waynegraham/dh-recipes/wiki/Style-Guidelines
[github-forking]: http://help.github.com/forking/
[github-pull-requests]: http://help.github.com/pull-requests/
[irc]: irc://irc.freenode.net/#slab
