# Merge Conflict
![GitHub Logo](/images/Image4.png)
1.	Merge conflict happens when programmers both make changes to the same line within a file or when a programmer is modifying a file that anther programmer had deleted. For example, when make changes to a file that is on a branch such as Master while you make another change using the same file on another branch such as feature. Once the changes had been made within the feature branch and you then merge the master while you are still in the feature branch. This is when the merge conflict occurred. 
There are different ways to avoid merging conflicts. First you can use the git difftool in which allow developers compare both files at the same time, side by side. 
![GitHub Logo](/images/Image5.png)
Below is a tutorial on how to create a merge conflict:
1. You want to create a new branch called "NewBranch"
	a. git checkout -b NewBranch
![GitHub Logo](/images/Image11.png)
2. Let's commit our new branch
	a. git commit
![GitHub Logo](/images/Image12.png)
3. Now let's work with master. Checkout Master. Do you see the asterisk(*)? It means that the branch is checkout.
	a. git checkout master
![GitHub Logo](/images/Image13.png)
3. Once checkout, lets edit the first line of the file.txt and commit within master.
a. git add file.txt 
b. git commit -m "Changing file in master”
4. Once you complete updating your file, lets now checkout NewBranch and edit the file.txt first line as well.
	a. git checkout feature
b. git add file.txt
c. git commit -m "Changing file in feature"
5. Once change lets now merge master. Be sure that the NewBranch is checkout.
	a. git merge master
![GitHub Logo](/images/Image14.png)

1.	**Forking** is exact replica of the repository where it allows developers to freely experiment such as changing coding without ever touching the original project. Basically forking resembles as a bridge connection between the copy and back to the original repository while utilizing the Pull Request.
2.	**Pull Request** notifies other developers concerning on any changes that someone had made towards a branch within GitHub.
3.	**Cloning** on the other hand only works with GitHub where its clone remotely and synced such as one on GitHub and the other repository on your personal desktop computer.

# Adding  collaborator to a GitHub Repo
1. Go to your respository that you are working in.
2. Look and click on "Setting" that is within the tab control.
	1. ![GitHub Logo](/images/Image20.png)
3. Look and click on "Collaborators" on the left sidebar.
4. Add all nesscary collaborators for the project by using their email address.
	1. 	1. ![GitHub Logo](/images/Image21.png)
5. Be sure that are users that were requested, must accpet your invitation.

