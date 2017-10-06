**What happens when you initialize a repository? Why do you need to do it?**
When you initialize a git repo, it creates the `.git` directory which is where
git will store metadata about your project's history. You need to do it so that
git can get things ready for you to make the first commit.

**How is the staging area different from the working directory and the
repository? What value do you think it offers?**
The staging area is where you put things that you are planning on including in
the next commit. The working directory is where are your files are stored, in
their current state. This allows you break off small logical commits as you
work, rather than always having to commit all changes you've made since your
last commit.

**How can you use the staging area to make sure you have one commit per logical
change?**
To ensure that you have one logical change per commit, you can add only the
changes that make up on logical change to the staging area, commit them, and
then continue these two steps until all of your changes are committed.

**What are some situations when branches would be helpful in keeping your
history organized? How would branches help?**
Branches would be helpful if you had multiple people working on the same repo at
the same time. Each person could work on a separate branch, and merge their
changes into master when their code has been peer reviewed.

They could also help you maintain different versions of your software. Each
release could be a long-living branch. To make a release, you'd branch off of
master. You'd keep this branch around, and when you want to add a bug fix to an
old version, you could cherry pick it off of the main branch.

You could also use branches to work on different features or bug fixes at once.

**How do the diagrams help you visualize the branch structure?**
Diagrams help me see when (i.e. what commit) a branch was created from. I can
see what changes each branch does and does not have.

**What is the result of merging two branches together? Why do we represent it in
the diagram the way we do?**
After merging two branches together, the changes from both branches are included
in the branch that is currently checked out. A visual representation of this
shows that the two branches diverged after a certain commit, and merged back
together on a certain merge commit. The branches are laid out next to each other
to communicate that when they existed, the changes on each branch were separate
from each other.

**What are the pros and cons of Git’s automatic merging vs. always doing merges
manually?**
It would be really tedious to always merge manually. Git can't always
auto-merge, even when you think it should, but it's nice that it will do it for
you in easy situations.
