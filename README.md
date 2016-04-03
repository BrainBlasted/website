# [The Open Source Club's Website](https://opensource.osu.edu)

[![Build Status](https://travis-ci.org/OSUOSC/open-source-club-website.svg?branch=master)](https://travis-ci.org/OSUOSC/open-source-club-website)
[![Dependency Status](https://gemnasium.com/OSUOSC/open-source-club-website.svg)](https://gemnasium.com/OSUOSC/open-source-club-website)
[![security](https://hakiri.io/github/OSUOSC/open-source-club-website/master.svg)](https://hakiri.io/github/OSUOSC/open-source-club-website/master)
[![Built with Grunt](https://cdn.gruntjs.com/builtwith.png)](http://gruntjs.com/)


This is our repository for our club's [website](https://opensource.osu.edu). It's built with [Jekyll](https://github.com/jekyll/jekyll), [Jade](https://github.com/jadejs/jade), [Sass](https://github.com/sass/sass), [Coffeescript](https://github.com/jashkenas/coffeescript), and [Grunt](https://github.com/gruntjs/grunt).

<br>
--
<br>

[Wiki](https://github.com/OSUOSC/open-source-club-website/wiki)

[How to contribute](https://github.com/OSUOSC/open-source-club-website/blob/master/.github/CONTRIBUTING.md)

Check out our [staging site](https://osuosc.github.io/open-source-club-website/), which may or may not be up-to-date

<br>
--
<br>

#### Fork, then clone the repo:
  ```bash
    git clone git@github.com:<username>/open-source-club-website.git
    cd open-source-club-website
  ```

--

<br>
#### Dependencies:
  - ruby `v2.2.3`
  - node.js `v4.2.6`

--

<br>
#### Set up your machine:
  ```
  ./init.sh
  ```

<br>
--
<br>

#### Build site locally and run development server:
  ```bash
    grunt serve
    # once compiled the site will be accessible at localhost:4040
  ```

<br>
--
<br>

#### Create new post

  ```bash
    ruby _helpers/newPost.rb
  ```
  
*posts that aren't generated using this helper script will be rejected*

<br>
--
<br>

for indepth instructions checkout our [wiki](https://github.com/OSUOSC/open-source-club-website/wiki/Running-the-Site-Locally)
