# Black Axe SASS Defaults #

Default set of files to use for new projects. This is still a work in progress. Feel free to contribute any changes that you think will help us out whenever you want.

Check out the Treehouse course that this was based on for more info http://teamtreehouse.com/library/modular-css-with-sass

### What are all of these files for? ###

* **/utilities/** - Things like variables, mixins, functions, etc
* **/utilities/_config.sass** - All of the site's default varibles (fonts/colors/etc)
* **/base/_base.sass** - Default element styles. Nothing with class names or IDs. You shouldn't have to mess with anything else in the /base directory
* **/modules/** - All of the site specific stuff with classes and IDs
* **/modules/_extends.sass** - SASS placeholders for all kinds of site specific values
* **/layout/** - Grid system specific stuff configuration
* **main.css** - The final outputted SASS file.

### What if I want to add stuff? ###

Just make a new branch and go nuts. Don't merge things to the master until we get some time to go over it or whatever.

### Current Issues ###

* Potential issue with Sass maps and .sass syntax. Haven't tested it out yet
* Don't know if we care to adjust all of the default colors to things that we like better just because.