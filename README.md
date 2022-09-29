# Portfolio
[Minh Huynh Portfolio](https://mhuynh.dev/)

## What it does
A responsive portfolio website written in HTML and CSS

## How I built it
* I wrote the site on Visual Studio to test it locally then deployed it on Oracle Cloud using Docker and Nginx
* Registed a .dev domain on Porkbun, made it pointed to my server public IP
* Installed SSL certificates to support HTTPS

## Challenges I ran into
* My webserver runs Ubuntu, and Docker has limited documentation for Ubuntu compare to Linux; therefore, it took me a bit more work to make it work.
* .dev domain by default redirects to HTTPS and does not support HTTP. This bugged me because I thought I did something wrong when trying to access the website via HTTP protocol and it did not load
* Certbot cannot be set up initially because, again, .dev does not support HTTP.

## Accomplishments that we're proud of
Being able to install Porkbun SSL certificate to Docker with Nginx on Ubuntu.
Because there wasn't an answer for this issue online, I figured it out on my own by reading the documentation of Docker and Nginx.

## What I learned
* Deployed a website using Docker
* SSH connection to an online server
* .dev and .app domain only support HTTPS

## What's next
Add pages for each project

## Built With
html css

## Try it out
[Minh Huynh Portfolio](https://mhuynh.dev/)
