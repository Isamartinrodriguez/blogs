**NOTE** this needs spell checking and some refinement. Some phrasing is too verbose and other phrasing is repetative. The goal of "quick to close" being in the best interest of constant product improvement may also need to be expanded upon from what I currently have...


# Issue Closing Announcement

Soon we will close and lock all open issues in the Ionic Framework issue list. We are not doing this because we think they are fixed. As a matter of fact, we _know_ that a lot of them are still issues. Here is what is going on:

* We are not going to fix any of this in the current release
* Some of these items **will** be fixed by the next major release
* Some of these items **will not** be fixed by the next major release
* The next major release of Ionic is right around the corner

With the next major release, we want to be able to effectivley manage the issues that are out there so we can fix issues quickly and release bug-fixes often and on a regular schedule. We cannot do that effectivly with the current issue list. We simply do not have the number of person-hours it would take to analyze, prioritize, and then work on the issues in the current list. Simply determining if something is still an issue or not after the next major release would be too big of a task on its own without actually fixing anything. So, we are starting over by closing and locking all outstanding issues immediatly before the next release.

Here is how the issue list will be managed going forward:

* team members will rotate being responsible for triaging new issues as they come in to ensure they get looked at promptly
* new issues will be automatically marked with a `triage` label which will be removed when the team member that is currently responsible for the list has analyzed the issue
* this issue list is **only** for reporting bugs or requesting new features, other items such as support requests will be closed and locked immediately
* issues that do not follow the issue template will be closed and locked immediately
* issues that cannot be duplicated will be labeled as such and close immediatly, but will remain unlocked for a period of time in case further information can be provided in order to help duplicate the issue
* significant issues should always be accompanied by a small sample program that has been pushed to a GitHub repo, if this is missing it will be asked for, but the issue will be closed and locked if it is not supplied within a reasonable period of time
* issues that have not seen activity from anyone (including us) shall be closed and locked, which does not mean the issue is solved, only that it is not currently something that anyone has time to work on
* feature requests will be labeled as such and left in the issue list rather than being moved to a private repo, allowing for better community visibility into the list of requested features

The goal of all of this is to ensure that the team is always working on fixing the most important issues out there, and that no important issues are being missed or burried. That can only be accomplished by a combination of actively fixing the issues that we can and agressively managing the rest of the issue list.