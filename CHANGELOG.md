* touch ~/.vimblogger_labels if it does not exist
* Markdown support using python-markdown2
* Added an `autocmd` for publishing post before writing file
* Change dictionary file (c-x c-k autocompletion) based on start of current
line, i.e. if line begins with @@, use ~/.vimblogger_labels, otherwise use
~/.vimblogger_words
* Check ~/.vimblogger_words at startup, if non-existent, create an empty file
with that name
