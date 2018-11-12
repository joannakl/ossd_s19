# Course website for CS480, Section 10 (Spring 2018)

Currently under class exercise experiment. 
Bugs to be fixed by students. 

This site is built with [Jekyll](https://jekyllrb.com/) and is hosted on [GitHub Pages](https://pages.github.com/).

## Setup
### [MacOS and Linux](https://jekyllrb.com/docs/installation/)
### [Windows](https://jekyllrb.com/docs/windows/)

## Building and Running
```
git clone https://github.com/joannakl/cs480_s18.git
cd cs480_s18
jekyll build --watch
open _site/index.html
```

Alternatively, if you want to build with a local webserver:
```
# in `_config.yml`, change the baseurl config to – `baseurl: ""`
jekyll serve
# navigate to http://127.0.0.1:4000/
```

Note: If you make any changes to  `_config.yml`, you have to restart the server or run `jekyll build --watch` for the changes to take place.

## Contributing
Please see [this document](/CONTRIBUTING.md) for instructions on how to contribute