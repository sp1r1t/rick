# rick
Definitely not a rickroll!


## How to run

It's a static HTML, you can just put it on a web server.

For quick local dev I recommend [http-server](https://github.com/http-party/http-server)

``` sh
npm i -g http-server
http-server .
firefox localhost:8080
```

## Features

* Serve rick directly as mp4
* No youtube or the like
* Autoplay enabled
* Deceiving pause button that enables the sound (can't be done on default anymore in modern browsers)
* Rick as a gif while loading (if the internet is slow you still know what hit you)
* Fallback to gif for browsers without js enabled
* Fullscreen
* Small square in the right bottom corner to pause and mute, for the initiated
