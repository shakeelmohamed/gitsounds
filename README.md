git sounds
=========

Everybody needs git sounds!

# Setup

* Have afplay (should be good to go on OS X)
* Clone this repo to `/home/git`, run 

```mkdir -p foo && cd /home/git && git clone git@github.com:shakeelmohamed/gitsounds.git```
* Copy file in `git/hooks` to any local repo's `.git/hooks` folder
* Just in case, run `chmod +x` when in your local repo's `.git/hooks` folder to make sure the scripts can be executed.

## Current sounds

* pre-push: plays a sample of the Scarface theme, "Push it to the limit!"
* pre-rebase: plays a sample of Swizz Beatz saying "Oh you fancy, huh?" from the chorus of Drake's "Fancy"
* post-merge: plays a chicken squawking
* post-checkout: plays a tree branch snapping

## TODO

* post-commit: ???