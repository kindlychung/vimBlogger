# Description

This small plugin enables you to publish (and update, to some extent) posts on www.blogger.com right inside vim! I have tried a few other plugins and didn't feel very happy, so decided to roll my own.

# Requirements

* Tested in Vim 7.4, but should also work on 7.3
* Python support is required, check `echo has('python')` in vim
* A few python packages, this shell command should do it:

    pip install gdata Beautifulsoup4 lxml

# Usage

Only two functions are provided:

* `Bnew`: create a new post
* `Bpost:` publish the current buffer as a post, or update it if it's already publilshed

Well, I told you, it's simple stuff. :-)



