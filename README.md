# ghw - Converts your GitHub wiki to gh-pages

This tool serves the content of your GitHub wiki pages using gh-pages. You can customize the UI and aggregate information (ie. localized versions) within the same site.

## Installation
1. git clone this repo.
2. install node.js (if you haven't already).
2. install globally using `npm install ghw -g`
3. cd to the <strong>demo</strong> folder 
5. Verify the installation by running `ghw`.
4. under the demo folder, clone a sample wiki (git clone git@github.com:bebraw/jswiki.wiki.git).
6. execute `./build.sh`. The reply should be "ghw 2.0.0".
5. create the <strong>out</strong> folder by executing `ghw -t templates -i repodir -o out`.

## Thanks

Big thanks to [Guillermo Rauch](https://github.com/rauchg) for motivating the project! The [Node](https://github.com/joyent/node) guys deserve thanks too.

## License

ghw is available under MIT. See LICENSE for more details.

