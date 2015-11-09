# Work and collaborate

This is just the beginning and here are some suggestions on how we should work
and collaborate on our subsequent projects.

This will evolve with time.


## Using Github

* Short and suggestive project name (Use underscore or hyphen to separate words)
* (Follow Git commit guides)[http://chris.beams.io/posts/git-commit]
  * Separate subject from body with a blank line
  * Limit the subject line to 50 characters
  * Capitalize the subject line
  * Do not end the subject line with a period
  * Use the imperative mood in the subject line
  * Wrap the body at 72 characters
  * Use the body to explain what and why vs. how

* Keep the master branch always clean
* New work should always be on a branch(lets call it `feature branch`)
* Create `pull request` to merge features into master
  * Someone else should always review before merging to master
  * Never merge `master` to a feature branch

## Conflicts will arise

#### If the `master` has changed while working on branch, try rebase to master

```
git pull master
git checkout feature-branch
git rebase master
```

This will keep our commit graphs linear. Also, resolve any conflict locally 
before pushing to Github.


## Hope this helps

Lets update this from time to time. :)
