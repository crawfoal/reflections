**How did viewing a diff between two versions of a file help you see the bug
that was introduced?**

When viewing the diff, I didn't have to do the work of scanning the files and
finding what was different between the two versions. That was already done for
me, so I was able to focus on the actual content of the diff, rather than
finding it.

**How could having easy access to the entire history of a file make you a more
efficient programmer in the long term?**

- easier to discard recent changes
- easier to find bugs
- when you don't understand a section of a code base, you can look back and see
  who the recent major contributors are, and ask them for help
- when you don't understand why someone wrote code the way they did, you can
  look back at their commit message and see if they gave an explanation
- you can work on different tasks within the code base at the same time and
  deal with merging the changes together when it is convenient

**What do you think are the pros and cons of manually choosing when to create a
commit, like you do in Git, vs having versions automatically saved, like Google
Docs does?**

When manually choosing when to commit, you can group changes logically by
content with one logical change per commit. When versions are automatically
saved, you don't have to remember to do it so changes will never get to be too
big.

**Why do you think some version control systems, like Git, allow saving multiple
files in one commit, while others, like Google Docs, treat each file
separately?**

Whether it makes sense to track individually or separately depends on the work
being done, as we saw in the quiz. Editing photos was an example of a type of
work in which it makes sense to track files individually. Usually, in
programming it makes sense to track the files together because we have code in
multiple files that highly interdependent.

**How can you use the commands git log and git diff to view the history of
files?**

- `git log` shows a history the commits that have been made.
- `git diff` shows you what changes were made.

**How might using version control make you more confident to make changes that
could break something?**

Version control makes it easy find what changes broke something and to go revert
back to the way things were before the bug was introduced.

**Now that you have your workspace set up, what do you want to try using Git
for?**

I already use it for all of my projects. I'm just reviewing.
