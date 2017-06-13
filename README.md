### Camp Kesem at the Claremont Colleges Newsletter - Jekyll Version


## Installation
1. Clone this repository
2. Install Ruby (>= 2.0.0) using homebrew or chocolatey
`brew install ruby`
3. Install Ruby Gems
`gem update --system`
4. Install the Jekyll gem
`gem install jekyll`
5. Run the server
`cd thisRootDirectory/ && jekyll serve --watch`
Then open up your browser and check
`localhost:4000`
6. If that doesn't work and you get a load error, make sure bundle is installed.
`gem install bundler && bundle install`
Then restart the server
```
jekyll serve --watch
```

## How to add posts
**Duplicate** the `newsletter.example.markdown` file and rename it with the following convention: *YYYY-MM-DD-newsletter.markdown*.
Edit the following top entries:
* title (title displayed on main page and largest header on article)
* subtitle (one sentence description of what's in the post)
* date (when this should be posted/visible)
* author
* header-img (the img path to your cover photo)

If your server is still running check `localhost:4000` and see if there is a new post there.

## What's Included

A full Jekyll environment is included with this theme. If you have Jekyll installed, simply run `jekyll serve` in your command line and preview the build in your browser. You can use `jekyll serve --watch` to watch for changes in the source files as well.

A Grunt environment is also included. There are a number of tasks it performs like minification of the JavaScript, compiling of the LESS files, adding banners to apply the MIT license, and watching for changes. Run the grunt default task by entering `grunt` into your command line which will build the files. You can use `grunt watch` if you are working on the JavaScript or the LESS.

You can run `jekyll serve --watch` and `grunt watch` at the same time to watch for changes and then build them all at once.

## Acknowledgements
Using #Clean by StartBootstrap

# campkesemclaremont.us
Camp Kesem at the Claremont Colleges Newsletter
