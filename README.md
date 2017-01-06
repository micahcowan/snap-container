# snap-container
Docker container for [Berkeley _Snap!_][1] ([GitHub][2]) code-block programming language web app, built upon the standard **httpd** container.

[1]: http://snap.berkeley.edu
[2]: https://github.com/jmoenig/Snap--Build-Your-Own-Blocks

## To consume
```
$ docker run -p 8080:80 -d micahcowan/snap
```
(and then open http://localhost:8080/ in your browser)

## Purpose
To make it easy to run _Snap!_ on a local machine, even if disconnected from the internet, and still retain access to the standard code libraries and example projects.
