# GOAT 2015 Website


## Setup

The static website is generated using [Jekyll](http://jekyllrb.com/), which is a Ruby based tool.

With Ruby installed, just run the following command to get the required gems installed
```sh
bundle install
```

Please note that this may take a while as `libv8` is a large gem.

## Run the server

```sh
jekyll serve
```

This by default will start the server on `localhost:4000`.
You can view the English content at [localhost:4000/en/](http://localhost:4000/en/) and the French content at [localhost:4000/fr/](http://localhost:4000/fr/)

## Images

All images are sized appropriately to reduce size. In addition, all images are
run through [tinypng.com](http://tinypng.com) to minimize their size. The goal
is to help the site load as quick as possible by minimizing size of files. A
non-critical TODO is to minify and combine files when/if possible.
