# [imgproxy](https://imgproxy.net/) for FreeFeed

Configuration (environment variables):

* `REMOTE_ORIGIN` origin of FreeFeed storage server. Default value: `https://freefeed-storage-test.s3.eu-west-1.amazonaws.com` (candy)
* `HTTP_PORT` public HTTP port. Default value: `8080`

Caddy from the container should have write access to `caddydata` directory.
