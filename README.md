# [imgproxy](https://imgproxy.net/) for FreeFeed

Configuration (environment variables):

* `REMOTE_ORIGIN` origin of FreeFeed storage server. Default value: `https://stable-media-r2.freefeed.net` (candy)
* `HTTP_PORT` public HTTP port. Default value: `8080`

## Usage

Start with `docker-compose up`

Enjoy the images!

* http://localhost:8080/attachments/210ffe57-2b27-4ca1-b892-d85d51b73243.jpg (original)
* http://localhost:8080/attachments/210ffe57-2b27-4ca1-b892-d85d51b73243.jpg?width=500&height=700 (resized)
* http://localhost:8080/attachments/210ffe57-2b27-4ca1-b892-d85d51b73243.jpg?width=500&height=700&format=webp (webp)
