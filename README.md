# Personal Website
The source code and documentation for my personal website and blog. Personal projects, blog posts, thoughts, etc are all aggregated here. See the [Wiki](https://github.com/FlatlanderWoman/portfolio/wiki) for more information.

## Table of Contents
* [Setup Instructions](#setup-instructions)
  * [Installing Jekyll and Building Locally](#installing-jekyll-and-building-locally)

## Setup Instructions
### Installing Jekyll and Building Locally
If Jekyll was successfully installed, a version number should've been printed out. Now that everything is correctly installed, you can run a local build of the site by executing the following into your BASH terminal:
```
$ bundle exec jekyll serve --watch --baseurl ""
```
This will build and run the site locally on port 4000 (i.e. `localhost:4000`). Visit said URL to view the site. **Note:** `bundle install/exec` will fail/crash when trying to bundle on Windows because of the nokogiri gem. 

---

[![Code Climate](https://codeclimate.com/github/FlatlanderWoman/portfolio.svg)](https://codeclimate.com/github/FlatlanderWoman/portfolio) [![Coverage Status](https://coveralls.io/repos/github/FlatlanderWoman/portfolio/badge.svg?branch=master)](https://coveralls.io/github/FlatlanderWoman/portfolio?branch=master) [![Build Status](https://travis-ci.org/FlatlanderWoman/portfolio.svg?branch=master)](https://travis-ci.org/FlatlanderWoman/portfolio)  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
