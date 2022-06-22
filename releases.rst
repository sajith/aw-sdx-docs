
Making a release
================

What is a release?
------------------

TODO

What do we release, and how?
----------------------------

TODO

Who can do a release?
---------------------

TODO

What goes into a release?
-------------------------

TODO

Release planning
----------------

TODO


Checklist
---------

First, check out the source code.

Tag the release in your local copy, and push it to the GitHub repository::

  $ git pull --rebase origin main
  $ git tag -s -m "initial release" 1.0.0 main
  $ git push ssh --tags 1.0.0

(Omit `-s` from `git tag`, if you have not set up a PGP key at
GitHub.)

And then, go to the repository in GitHub, and do so:

 - Click on "create a new release".
 - Chose the tag that you just pushed.
 - Add a release name and some release notes.
 - Check the "this is a pre-release", if it is a pre-release
 - Clicked the big green "publish release" button

Et voila! We have a release.
