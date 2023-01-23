# Project 2
For the second activity you will contribute to a project. Here is the link to the repository, https://github.com/HamoyeHQ/Version-ctrl-with-git.git 

1.Fork the repository.
2.Clone the repository, so you can have a copy of the repository on your local machine.
3.Create a new branch 
4.Contribute
5.Stage changes
6.Commit changes
7.Create a pull request (PR)

#Solution

1. To "fork" the repository, go to the repository, click on "fork" and select which account to copy the repository to. 

2. Copy the link to your version of the repository.

3. To clone the repository, go to the folder where you want the repository to be copied to and "git bash" here. Then run the command to clone a repository.

git clone url

4. Close the "git bash", open the cloned repository and do "git bash" here.

5. Create a branch. You can name the branch anything, but it’s preferable to use your name. You can do this by running the command;

## git branch branchname

![image](https://user-images.githubusercontent.com/93423367/214071452-289edee9-6507-46c0-8317-61e5d0eefe09.png)

6. Switch to the new branch using the git checkout command;

Git checkout branch name

![image](https://user-images.githubusercontent.com/93423367/214071538-3a5828f5-82ba-4675-9bfa-6bf976cbf763.png)

7. Edit the attendance.txt file using any text editor. Add your name to the list of names. Save and exit.

8. “git  add” to stage the changes

“git add. “

9. “Git commit” to commit the changes,

![image](https://user-images.githubusercontent.com/93423367/214071645-fe413b63-0092-4cf5-b0fe-0b259d6db48f.png)

10. Switch to the master branch

git checkout master.

11. Pull changes so that your copy can be up to date with the remote repository.

Git pull origin master

![image](https://user-images.githubusercontent.com/93423367/214071764-8636af0f-8bd5-49a1-8237-05572b35fca3.png)


12. Push your branch to the remote repository.

First switch back to your new branch

Then push

Git push -u origin branch name

![image](https://user-images.githubusercontent.com/93423367/214071856-98b4bd73-6beb-404e-9407-7809b9f335d2.png)


Yes, we just pushed to the remote repository, but we need to create a PR to notify the owner of the repository that we want to make changes, 

13. Make a Pull request (PR).

If you check the message after the push command, you will get the link to create the pull. For example, 

https://github.com/zalihat/Version-ctrl-with-git/pull/new/attendance 

14. Follow the link to create a PR

The link will look like this;

![image](https://user-images.githubusercontent.com/93423367/214071969-57c68008-5cee-4927-b89c-f07ab37f7d9a.png)

Create the Pull request and wait for the reviewer to merge your pull request.

You will get a notification once your pull request has been merged.

Congratulations, you have successfully contributed to another person’s repo. This is how you contribute to open source projects.















































