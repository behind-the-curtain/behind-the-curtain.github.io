## the grove church website.

### developing

start up a server:

```
$ git clone git@github.com:groveatx/groveatx.github.io.git
$ cd groveatx.github.io
$ jekyll server --watch
```

and [open it in your browser](http://localhost:4000).

note that `css/style.css` is generated by the jekyll build, so if you want to
edit styles you gotta have jekyll and lessc in your `$PATH`.

### deplying

just push to the github repo to deploy to the github page, or put the `_site`
directory on a server somewhere.

## license and copyright

everything in the `_posts` and `_includes` directory is &copy; 2013 The Grove
Church.

all non-third-party code is licensed under the included MIT license listed in
the LICENSE file in this same directory.
