Additional Git Commands
=======================

Contains additional useful git commands.

Requirements
------------

* Git v2
* [Hub v2](https://hub.github.com/)

Installation
------------

Clone this repo and add the directory to your `PATH`.

```sh
git clone https://github.com/highwayoflife/git-scripts ~/.git-scripts
echo "export PATH="${HOME}/.git-scripts:$PATH" >> ~/.zshrc
```

Commands
--------

* `git activity` - Pretty-print log activity across all branches.
* `git merge-pr <PR-NUMBER>` - Merge a desired Pull Request to Master
* `git merge-branch` - Pull-Request Merge current Branch to Master
* `git create-pr` - Shortcut to push branch and create a pull-request

Contributors
------------

* [David Lewis](https://github.com/highwayoflife)

License
-------

[MIT](LICENSE)

