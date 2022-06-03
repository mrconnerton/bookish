# Bookish

[Bookish] is an install profile for Drupal 9+ that tries to make the out of the
box experience for [Tome] users as nice as possible.

This is a skeleton repository built on top of `drupal/core-recommended` and [DDEV].

To get started with this skeleton:
- `git clone git@github.com:mrconnerton/bookish.git && cd bookish`
- Alter `.ddev/config.yaml` to change the name and other ddev config.
- `ddev start && ddev install`
- `git remote remove origin` so you can a1dd your own origin.

The skeleton project does not include the exported configuration. The install process will show untracked and possibily altered files in git.

Follow these links to learn more about each part:

- [Demo Site]
- [Tome]
- [Bookish]
- [DDEV]

[Demo Site]: https://bookish-drupal.netlify.app/
[Tome]: https://tome.fyi/docs/
[Bookish]: https://github.com/drupal-tome/bookish
[DDEV]: https://ddev.readthedocs.io/en/stable/
