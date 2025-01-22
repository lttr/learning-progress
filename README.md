# My learning progress

This is an attempt to document my learning more systematically. Git commit
messages could be the way to document historical progress of anything, while
Github issues cover things in two states very nicely: open issues and closed
issues.

Interesting topics, courses, videos and books goes to open issues.

Closing an issue means I've completed the book or course. I could eventually
delete an issue if I found it is a very bad resource.

Closing an issue as not completed means I've skipped the topic or course but may
revisit it in the future.

Commits are the actual progress. Git log in this repo will give me an instant
overview of my recent learning progress.

## Examples

Create a learning topic

```bash
cd ~/code/learning-progress
gh issue create -t "Topic" -b "url or other content"
```

Add note about progress

```bash
cd ~/code/learning-progress
git commit --allow-empty -m "Start course #1"
git commit --allow-empty -m "Finish course, close #1"
# with alias
ce "Finish course, close #1"
```
