# Project2gitpractice
**A .STEPS INVOLVE IN iNITIALIZING A GIT REPOSITORY**

- After installing git on your laptop through this link [visit github.com](https://www.github.com)
- Open a terminal on your computer through e.g gitbash or visual studio code.
- On your terminal create your work folder or make directory using the this command: **mkdir Devops**
- Change or move into your folder using this command: **cd Devops**
- While you are inside the folder run the command:**git init**
  
![image001](https://github.com/DevopMudi/Project2gitpractice/assets/149855241/57eddeea-f868-4331-8534-17f6ca87b276)

**B. STEPS INVOLVE MAKING A FIRST COMMIT**

- Inside your work directory create a file using: **index.txt**
- Write any sentence of your choice inside the text file after which save it.
- add your changes to git staging area using this command: **git add .**
- To commit your changes to git run this command: **git commit -m " first commit"**

  ![image003](https://github.com/DevopMudi/Project2gitpractice/assets/149855241/aabdf357-c564-44b1-af2a-91137f577e90)


**C. HOW TO MAKE A GIT BRANCH**
- Having make your first commit, make a new branch running this command: **git checkout -b**
- 
![image005](https://github.com/DevopMudi/Project2gitpractice/assets/149855241/7f167370-e352-447d-b3fd-cd7c5a37516a)


**C. HOW TO KNOW HOW MANY BRANCH THERE ARE**
- Run this command: **git branch**

  ![image007](https://github.com/DevopMudi/Project2gitpractice/assets/149855241/1425aadb-bee3-4b99-ad0c-eac6ddff8a04)

**D. HOW TO CHANGE INTO AN OLD BRANCH**
- Run this command: **git checkout <branch_name>**

![image009](https://github.com/DevopMudi/Project2gitpractice/assets/149855241/fb8bf4e3-6dfd-4507-942a-2018f926a24d)

**E. MERGING BRANCH INTO ANOTHER BRANCH**
- Lets say we have two different branches, branch A and branch B,and we want to merge the content inside the branches to make one branch,
- first, we change into branch A and Run this command: **git merge B**

![image011](https://github.com/DevopMudi/Project2gitpractice/assets/149855241/4df2b453-73e4-4c42-9e94-5b506c6f78b9)

**F. DELETING GIT BRANCH**
- When new features is added to an application, it is often done in a feature branch, usually this feature branch is deleted when the code must have been tested and
-  merge into a staging area or dev environment depending on the branch strategy of the team.
-  Git branch can be deleted with ths command: **git branch -d**
-  However, to learn more on git brach -d, we can look into the following command for more ways we can use this command: **git branch --help**

![image013](https://github.com/DevopMudi/Project2gitpractice/assets/149855241/20f1321c-9f4e-475d-99fc-53cb8a7dcf51)

**G. STEPS IN CREATING A GIT HUB ACCOUNT**
- Head over to join git hub [visit github.com](https://www.github.com)
- After joining enter, your username,password and email to login
- verify your account
- Next click the create botton to creat your account. Its an easy step just follow through.

**G. CREATING YOUR FIRST REPOSITORY**
- Click on the plus sign at the top right corner of the github account.
- A drop down menu will appear, select New Repository
- Fill out the form by adding a new repository name, description and tick the box to add the **README.MD** file
  
![image](https://github.com/DevopMudi/Project2gitpractice/assets/149855241/72f09df2-ee38-4b99-8abe-62d9328cccc7)


- After filling the form click on create repository at the bottom.


**H. PUSHING YOUR LOCAL GIT REPOSITORY TO YOUR REMOTE GITHUB REPOSITORY**
- Add a remote repository to the local repository using the command **git remote add origin https://github.com/DevopMudi/Project2gitpractice.git**

![image019](https://github.com/DevopMudi/Project2gitpractice/assets/149855241/5a97dc6f-58be-4905-b156-4d596b37970a)

- Note: to get the remote link, click on the green botton code and copy link
![image](https://github.com/DevopMudi/Project2gitpractice/assets/149855241/f5156dde-4849-46f5-956b-07e11a42c3fb)
  
- After commiting your changes in your local repo, you push the content to the remote repo, using the command: ** git push origin <main branch>**

![image020](https://github.com/DevopMudi/Project2gitpractice/assets/149855241/bbf83cf3-08b7-4a41-9ccd-6fc6209d3a36)


**H. CLONING REMOTE GIT REPOSITORY**
- To clone use this command: **git clone <link to your remote repository>**

![image022](https://github.com/DevopMudi/Project2gitpractice/assets/149855241/0e9c617f-ae87-4e17-a657-a3c514139804)


For more Information visit :**[visit darey.io](https://www.darey.io)**













