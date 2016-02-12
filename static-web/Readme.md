# Docker container for Apache HTTP
Allows deploying of static html/css/js websites in a docker container.

## Setup
1. Copy your website into `public-html` folder. If you want the website to be deployed under a root like `/mywebsite` then copy your website into `public-html/mywebsite` folder. However, if you want it available at root then simply copy the entire folder contents directly in `public-html`.
2. cd into static-web container and build the image using standard docker build command.
