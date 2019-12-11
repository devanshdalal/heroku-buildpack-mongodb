Heroku buildpack: MongoDB Client
=======================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) containing the [MongoDB](http://www.mongodb.org/) client.

Usage
-----

Example usage:

    $ heroku create --stack cedar --buildpack http://github.com/devanshdalal/heroku-buildpack-mongodb.git

    $ git push heroku master

    $ heroku run mongo --nodb
