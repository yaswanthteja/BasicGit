


To put all we have learnt together, let's do a little project. Here are the instructions.

Activity 1
1.Create a  folder and name it whatever you want.
2.Run the “Git init” command to initialize the folder as a git repository.
3.Make changes to the folder; you can add whatever file you want.
4.Stage the changes using “git add” command.
5.Commit the changes with git commit.
6.Create a remote repository.
7.Link the local repository and remote repository.

# Solution

1.Note that when you create the folder you have to open the folder before you do "git bash" as shown below; I am stressing this because a lot of people make this mistake, even experienced developers.

![image](https://user-images.githubusercontent.com/93423367/214069283-796fbfa2-4e8b-4864-984b-27859045cb2f.png)

2.Run the git init command

![image](https://user-images.githubusercontent.com/93423367/214069348-ea7e661b-f0b6-4971-8fd2-a9df8b78351f.png)

3.  Make changes
![image](https://user-images.githubusercontent.com/93423367/214069441-311ee773-dbc9-408b-af78-f30737b1ef0d.png)

4. Git status
![image](https://user-images.githubusercontent.com/93423367/214069533-861dffd7-0373-4785-94ca-036d865717b6.png)

5. Stage changes, git add filename or git add . to stage all changes,

![image](https://user-images.githubusercontent.com/93423367/214069606-1fd483d7-28bc-4c7b-8d61-de13d6494af6.png)


6. Commit changes;

![image](https://user-images.githubusercontent.com/93423367/214069690-7e75602c-65cc-482e-a6f9-fa6dbddd832e.png)

7. Create a remote repository and name it  the folder name.

![image](https://user-images.githubusercontent.com/93423367/214069801-f63f6bc5-91b3-445a-90a5-51295a1d5acf.png)

![image](https://user-images.githubusercontent.com/93423367/214069843-a5982e92-0cbd-4fc3-9763-3d17e55b4384.png)

![image](https://user-images.githubusercontent.com/93423367/214069875-1b6cd28c-3319-42dd-a8c9-b084d354d292.png)

8. To  link both repositories. Copy the remote repository’s url. Click on code, and copy the link

![image](https://user-images.githubusercontent.com/93423367/214069965-37b0ae57-2590-4d45-9e05-a77902a40e42.png)

Go back to "git bash" and run

Git remote

This will return nothing, because we don't have any remote repository linked yet, to link the repository run the command

Git remote add origin [url]

To paste the url, use the insert key on your keyboard.

Make sure you copy the url, then type git remote, add origin, then press  insert key. 

![image](https://user-images.githubusercontent.com/93423367/214070047-754a4ba0-f46d-4e2a-b78c-584025b075d9.png)


9. “Git push” to push changes to the remote repository.

git push origin master
![image](https://user-images.githubusercontent.com/93423367/214070172-d4234569-2c8a-46a1-b967-728e7232be40.png)

10. Compare and pull request;

![image](https://user-images.githubusercontent.com/93423367/214070240-b18f1559-4f40-483d-a319-8a5eb680edca.png)


11. As shown above, the changes are not reflecting because the branch we pushed to was master not main. Hence, just click on  “main “and change it to “master” as shown below;

![image](https://user-images.githubusercontent.com/93423367/214070342-a7999885-b5f8-4396-9979-d247e2864623.png)

Copy the link to your repository as shown below;
![image](https://user-images.githubusercontent.com/93423367/214070429-d7a0f07c-0a1f-4df6-a44b-c03983ed4494.png)

Congratulations, You have successfully created a local repository, made changes to it, created a remote repository, linked it to the local repository, and pushed your changes to the remote repository. Now you can share your code with friends by just copying the link to the repository. Easy, yeah?. Copy the link to your repo and share it with me. Note that this is not compulsory. 
























