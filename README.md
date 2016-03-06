# Pintresting a Pintrest Clone

## Setup

Clone to desktop and run:

rake db:migrate to setup databases

ImageMagic will need to be installed on your dev machine

## Production

For production run on Heroku Amazon S3 was setup

Enviroment variable will need to be added based on your own Amazon S3 bucket.


heroku config:set AWS_BUCKET=`bucket name`

heroku config:set AWS_ACCESS_KEY_ID=`your access key`

heroku config:set AWS_SECRET_ACCESS_KEY=`your secret`




by [Nic Ollis](http://ollis.me)
