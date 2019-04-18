
# Beginners Guide to Git
### By Kelly 1904


![Internet for cups](https://imgur.com/0kzok1k)

**What is Git?**

To make things easy you can think of Git as a hidden file or program. It can see all the things you do to your files and it can help to make sharing those files easy! 

**Lets Look At What Git Can Do**

Git is really used for adding data. It also is really great at making save points for that data as well for any changes that are made at later dates. To better understand this we need to know the three states your files can live in with Git.

* **Committed**
	* The committed stage means that the data is safely stored in your database.
* **Modified**
	* You've made changes to your file but have not saved and committed those changes yet. When youre working on something it will be in the Modified state.
* **Staged**
	* Like the name suggests, the Staged state means that youve made your changes and they're ready to go on. The Staged state is when you've finished making the changes you would like on your file and are ready to have them committed.  

You might be wondering what thoes stages look like. Here's an example. 

1. You modify files in your workstation
2. You stage the files that are ready to be part of your next commit.
3. You do a commit, which takes those and only those staged files and sends them into your Git directory. 


**Git Commands**

Now that you know all about the states, lets *git* into learning the commands that are used when interacting with Git. 

Here are some common ones to know and remember!

`$git init` Git init is used to initalize a repository in an existing directory. What that means is, you have a file that you want to be able to use git with and its never used it before.

`$git add` Git add is used when you've made some changes to your file and want to send them from the modified state to the staging area. 

`$git commit` Git commit is used when you've gotten all your desired changed into the staging area and are ready to send them to your repository. 

`$git clone` Git clone is used when you want to get a copy of an existing Git repository. 

`$git status` Git status is a great command to use often. You can check what state you're in with this command. 


	$ git status
	On branch master
	Your branch is up-to-date with 'origin/master'.
	
There is moch more to know and lear with Git. These are only the building blocks of what it can do!



