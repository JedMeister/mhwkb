# Contributing
* [Code of Conduct](CODE_OF_CONDUCT.md)
* [List of Contributors](CONTRIBUTORS.md)

## Communication
  * [Gitter Chat](https://gitter.im/mhwkb/Lobby)
  * [Create or Discuss Issues](https://github.com/andy5995/mhwkb/issues)

## Tags
* tags should be specific
* links that discuss many different types of mental health issues should be
tagged using keywords that the article focuses on, not with each disorder
listed
* Don't use the tag "mental health". Every link in the KB should be related
to "mental health", which makes the tag unnecessary.
* Don't use synonyms. (ex. "veterans" is good, but don't add military. It's
implied. If the links is more broadly about the military, then it's okay to
use "military" and "veterans".
* If you're not sure, don't spend any time worrying about it. Ask in the Gitter
room or make a comment when you submit your pull request.

## Notes on Categorization
Links starting with:
* the word _a_ (ex. A)
  * are in Knowlege_Base/01_a.md
* the letter _a_ (ex. Anatomy)
  * are in Knowlege_Base/01a.md
* the word _How_
  * are in Knowlege_Base/01_how.md
* the phrase _Mental Health_
  * are in Knowlege_Base/01_mental_health.md

## Note to those with Collaborator access
* Don't push directly to the remote upstream. Make the changes on your fork
and submit a PR.

## Pull Requests
1. Fork the repo (if you haven't already done so)
2. Clone it to your computer
3. When you're ready to work on an issue, be sure you're on the **master** branch. From there, [create a separate branch](https://github.com/Kunena/Kunena-Forum/wiki/Create-a-new-branch-with-git-and-manage-branches) (e.g. issue_32)
4. Make your changes. If you're unsure of some details while you're making edits, you can discuss them on the ticket or in the [Gitter chat room](https://gitter.im/mhwkb/Lobby).
5. Commit your changes
6. Push the working branch (e.g. issue_32) to your remote fork.
7. Make the pull request (on the [upstream **master** branch](https://github.com/andy5995/mhwkb))
    * Do not merge it with the master branch on your fork. That would result in multiple, or unrelated patches being included in a single PR.
8. If any further changes need to be made, comments will be made on the pull request.

It's possible to work on two or more different patches (and therefore multiple branches) at one time, but it's recommended that beginners only work on one patch at a time.

### Syncing ###
Periodically, especially before starting a new patch, you'll need the sync your
repo with mine (remote upstream). GitHub has instructions for doing this:

1. [Configuring a remote for a fork](https://help.github.com/articles/configuring-a-remote-for-a-fork/)
    * For step 3 on that page, use https://github.com/andy5995/mhwkb for the URL.
2. [Syncing a Fork](https://help.github.com/articles/syncing-a-fork/)
    * On that page, it shows how to merge the **master** branch (steps 4 & 5 of **Syncing a Fork**).
