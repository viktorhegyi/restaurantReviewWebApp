This project was made as part of Google Udacity Front-End Web Developer Nanodegree Program.

For thes Restaurant Reviews projects, I had to incrementally convert a static webpage to a mobile-ready web application. I had a static design that lacks accessibility and I had to convert the design to be responsive on different sized displays and accessible for screen reader use. I also began converting this to a Progressive Web Application by caching some assets for offline use.

### How to start the site?

1. Clone or download this repository.

2. In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer.

In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

3. With your server running, visit the site: `http://localhost:8000`

## Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to replace `<your MAPBOX API KEY HERE>` in main.js with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information.
