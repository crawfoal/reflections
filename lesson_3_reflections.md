**When would you want to use a remote repository rather than keeping all your work local?**
Remote repositories are helpful when you're collaborating with other developers.
They also serve as a backup of your source code. Finally, when you use a hosting
service like Heroku, you deploy new changes to your project by pushing the
changes to a remote repository on their servers.

**Why might you want to always pull changes manually rather than having Git
automatically stay up-to-date with your remote repository?**
If you're in the middle of working on something, it might be confusing to
suddenly see changes to the code base that you didn't make. Along those same
lines, the changes in the remote repo might have conflicts that you need to
resolve. You'd want to wait to do this until you're ready.

**Describe the differences between forks, clones, and branches. When would you
use one instead of another?**
A fork is something you do on GitHub. If you want to make changes to another
person's repository, you should start by forking. You do this whether or not
you plan on proposing that the other person incorporates your changes into their
repo. A clone is a copy of a repo. You do this when you want to get a remote
repo on your computer, or you might use this locally if if you want to use a
project on your computer as a starting point for another project. A branch is a
way of keeping track of different versions of a single project. Branches are
created *within* a repo, whereas the other two create new repos.

**What is the benefit of having a copy of the last known state of the remote
stored locally?**
Because our local computer has a copy of the last known state of the remote
repo, it can only download the changes since then, rather than the whole repo.
It also gives information needed in order to merge the local and remote changes.

**How would you collaborate without using Git or GitHub? What would be easier,
and what would be harder?**
When I was a TA in grad. school, we had a shared dropbox folder where we kept
course materials like projects and homework solutions. There wasn't an easy way
to see the editing history of these material and as a result, things didn't get
updated and corrected as often or consistently as they likely would have if we'd
been using something like git and GitHub. We didn't have to deal with branches
and remotes, so in a sense that was easier, but not really worth the trade off.
We just didn't know any better! :)

**When would you want to make changes in a separate branch rather than directly
**in master? What benefits does each approach have?**
Making changes in a branch rather than in master opens up the opportunity for a
pull request, which is an important part of collaborating with others. You could
open up a pull request from your fork's master to the upstream's master branch,
but this isn't the best idea, especially when you're working on multiple
features or bug fixes. By making your changes in a separate branch, you have
control over when to merge upstream changes into the branch your working on. You
can reserve the master branch of your local repo for syncing with the upstream
repo, and then if you're working on multiple features you can choose to pull the
most recent changes into each feature branch at different times, only doing it
when each branch is ready.
