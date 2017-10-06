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
