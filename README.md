# Description

This small plugin enables you to publish (and update, to some extent) posts on www.blogger.com right inside vim! I have tried a few other plugins and didn't feel very happy, so decided to roll my own.

# Requirements

* Tested in Vim 7.4, but should also work on 7.3
* Python support is required, check `echo has('python')` in vim
* A few python packages, this shell command should do it:

<pre>
pip install gdata Beautifulsoup4 lxml
</pre>

# Installation, setup and usage

I have already used this plugin to post these info on my blog, you can see it there:  <a href="http://www.kaiyin.co.vu/2014/07/publish-to-blogger-right-from-inside-vim.html">Publish to blogger right from inside Vim! | Math notes and technical stuff</a>


# Change log

* touch ~/.vimblogger_labels if it does not exist
* Markdown support using python-markdown2
* Added an `autocmd` for publishing post before writing file
* Change dictionary file (c-x c-k autocompletion) based on start of current
line, i.e. if line begins with @@, use ~/.vimblogger_labels, otherwise use
~/.vimblogger_words
* Check ~/.vimblogger_words at startup, if non-existent, create an empty file with that name


# Todo

* Migrate to Blogger API v3
* Use oauth instead of password
