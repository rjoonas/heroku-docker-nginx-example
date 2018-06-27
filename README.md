# heroku-docker-nginx-example

Barebones example of deploying
[the official nginx Docker image](https://github.com/docker-library/docs/tree/master/nginx)
to Heroku. Serves an example html file at the root directory.

## Try it now!

Fire up an nginx proxy on [Heroku](https://www.heroku.com/) with a single click:

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Manual deployment

You will need to create a Heroku account and install the Heroku CLI, eg.
`brew install heroku`.

```
git clone git@github.com:rjoonas/heroku-docker-nginx-example.git
cd heroku-docker-nginx-example
heroku container:login
heroku create
heroku container:push web
heroku open
```
