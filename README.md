
This is an "intro to git" assignment for Math 607.  

Before you do this, go through the exercises at http://try.github.io.

BIG CAVEAT: it's been a while since I used git this way!  I know all of what I'm saying is entirely possible to do in git, but I might not have remembered the right way to do it.

Clone this repository using "git clone".  Then pretend it's a paper you're writing.

1. Make a version that's ready to go on the arXiv.  Add a bibliography. 

2. As you fix errors, add files, and so forth, keep the repository up to date with the commands "git add" and "git commit".

3. Make a horrible mistake, save it, commit the mistake, and use git to undo what you've done.  I suggest using "git revert" to undo the last commit.

4. Your paper is now on the arXiv.  Make an "arxiv branch" of your repository with "git branch", so that even if you change other stuff, you've got the source code for the version of your article which everybody uses.

5. You decide to submit the paper to an Elsevier journal, which requires you to use elsarticle instead of amsart.  You prefer the way your paper looked originally, though, so you decide to leave the arxiv version the way it is.  Make a "journal" branch with "git branch", and fix things so that the paper compiles under the elsarticle class.  Invariably this seems to involve messing around with the theorem commands somehow.


6. The journal refuses to publish the appendix of your paper because it's too long.  Delete the appendix from the journal version only.

7. Your colleague points out that 51 is not a prime number, and perhaps another couple of subtle errors.   Update both versions of your paper.






