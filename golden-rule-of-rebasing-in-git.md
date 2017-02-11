# The Golden Rule of Rebasing
[The Golden Rule of Rebasing, GitKraken](https://blog.axosoft.com/2016/10/20/golden-rule-of-rebasing-in-git/)

Rebasing is a topic that comes up all the time when using Git. Many times, rebasing results in having to do a force push, which makes some people wary of rebasing. No need to worry! Once you understand why a force push is necessary, and how to rebase responsibly, you’ll feel more comfortable.

So, what is rebasing, and how do you rebase in Git? Rebasing is simply taking changes that have been made somewhere else, incorporating them into your branch, and then replaying all of your changes on top of that new base.

**The Golden Rule of Rebasing reads: “Never rebase while you’re on a public branch.”**

You’re in fact, changing the commit history, which Doc taught us could have disastrous consequences. (Especially if you run into your future self.)

## The Timeline
I made a new repo in GitKraken, a cross-platform Git GUI, featuring some main plot points from Back to the Future. First, Marty is sent back to 1985. You’ll see I created a new timeline branch that has a couple of commits representing the events that follow. Then, I pushed the timeline branch up to GitHub.