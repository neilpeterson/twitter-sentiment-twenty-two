# Twiter Sentiment Twenty Two

Rebuild of a Python app from many years back. Goal is just a more modern golang based distributed app for experimentation purposes.

## Components to build

- Ingress - get tweets, place in queue
- Process - process tweet, store in database, load in cache
- Visualize results
- Results API

export TWITTER_CONSUMER_KEY=S1juYjQD9bH0i3dDxEOv2g7wE
export TWITTER_CONSUMER_SECRET=HHjLe1zZz9ydAZVbYurQRv8A8w4aAZbmqQqwBHFeyoAnsp9zI4
export TWITTER_ACCESS_TOKEN=556115100-7fhYvVvDLhwxHoj0TvgtvHBSedAvtPojsPNWnSJP
export TWITTER_ACCESS_SECRET=xkouLtiC9GCV8aM0DRvKLthcy7a2f7e4JhawIbs0subA7

$env:TWITTER_CONSUMER_KEY = "S1juYjQD9bH0i3dDxEOv2g7wE"
$env:TWITTER_CONSUMER_SECRET = "HHjLe1zZz9ydAZVbYurQRv8A8w4aAZbmqQqwBHFeyoAnsp9zI4"
$env:TWITTER_ACCESS_TOKEN = "556115100-7fhYvVvDLhwxHoj0TvgtvHBSedAvtPojsPNWnSJP"
$env:TWITTER_ACCESS_SECRET = "xkouLtiC9GCV8aM0DRvKLthcy7a2f7e4JhawIbs0subA7"