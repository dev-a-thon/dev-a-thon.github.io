# dev-a-thon.github.io

# Contribution Guidelines

### Git workflow

* Fork this repo using the button at the top.
* Clone your forked repo locally.

```
$ git clone git@github.com:yourname/dev-a-thon.github.io.git
```

* Don't modify or work on the master branch, we'll use it to always be in sync with the upstream.

```
$ git remote add upstream git@github.com:dev-a-thon/dev-a-thon.github.io/.git
$ git fetch upstream
```

* Do your coding and push it to your fork.

* Do a new pull request from your fork to dev-a-thon/dev-a-thon.github.io "master".



#### How to keep your local branches updated

To keep your local master branch updated with upstream, regularly do:

```
$ git fetch upstream
$ git checkout master
$ git pull --rebase upstream master
```
