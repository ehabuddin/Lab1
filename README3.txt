Exercise 7:  Using a Remote Repo for collaboration
Now lets see what happens when more than one person uses the same remote repo at once.
Use a shared remote repository
Find a partner.     
Make a new shared repo, or share one of your existing repos.  See previous exercises.
Each add a new file
One of you should create README3.txt, and one should create README4.txt.  Add about ten lines of text to each one.
Each of you should add and commit your changes locally, then push them to your shared repo.
You should see both new files show up on github.com.
You should each do a git pull and you'll see both new files show up locally.
Since you're just adding new files, these changes can't create any merge conflicts.  Let's try something a little more interesting:
Each edit the same file, different lines.
In your local working directories, each edit README3.txt.    One of you should make a very visible change to line 1, and the other should make a very visible change to line 10.
Each of you should stage (add), commit, pull (fetch and merge), then push, as before. Depending on timing, one of you should see an automatic merge during their pull.  Git can easily perform this merge automatically since the changes are on different lines of the file: git just performs both changes.
