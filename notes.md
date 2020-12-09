# This is a markdown file
See information on makdown on wikipedia:
https://en.wikipedia.org/wiki/Markdown

# Notes on git
When a directory has been added to git by mistake. If you want to
remove it from git without deleting it from your system. Example: `.idea/`
You can use the following git command:

    git rm -r .idea --cached

For the same situation with a file `file.py` you ommit the `-r`:

    git rm file.py --cached

It is the `--cached` flag that makes the difference.
