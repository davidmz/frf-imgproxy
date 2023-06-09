# [imgproxy](https://imgproxy.net/) for FreeFeed

Configuration (environment variables):

* `REMOTE_ORIGIN` origin of FreeFeed storage server. Default value: `https://freefeed-storage-test.s3.eu-west-1.amazonaws.com` (candy)
* `HTTP_PORT` public HTTP port. Default value: `8080`

Caddy from the container should have write access to `caddydata` directory.

## Usage

Start with `docker-compose up`

Enjoy the images!

* http://localhost:8080/attachments/210ffe57-2b27-4ca1-b892-d85d51b73243.jpg (original)
* http://localhost:8080/attachments/thumbnails/210ffe57-2b27-4ca1-b892-d85d51b73243.jpg
* http://localhost:8080/attachments/thumbnails2/210ffe57-2b27-4ca1-b892-d85d51b73243.jpg
* http://localhost:8080/attachments/2k/210ffe57-2b27-4ca1-b892-d85d51b73243.jpg
* http://localhost:8080/attachments/thumbnails2/210ffe57-2b27-4ca1-b892-d85d51b73243.jpg?format=webp
* http://localhost:8080/attachments/thumbnails2/210ffe57-2b27-4ca1-b892-d85d51b73243.jpg?format=avif
  
