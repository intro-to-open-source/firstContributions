# firstContributions
This repo allows Open Source beginners to learn how to contribute to Open Source Projects on Github!

Inspired by https://github.com/firstcontributions/first-contributions, this repo provides a smaller version of this project for the Red Hat BUILD event. 

Follow these steps to create your first contribution!

##
## PREREQUISITES

Git, a Github account, and a Text Editor are required to complete this contribution, and is also a standard toolkit for contributing to most open source projects.

- Git: https://git-scm.com/downloads

- Github Account: https://github.com/join

- Text Editor: 
  Examples include: 
  - Sublime Text: https://www.sublimetext.com/3
  - VSCode: https://code.visualstudio.com/download
  - Notepad++: https://notepad-plus-plus.org/downloads/
  



## STEP 1: Fork the Repository
At the top right corner of this github repository, click the "Fork" button.

![Screenshot from 2020-10-01 10-14-33](https://user-images.githubusercontent.com/6632748/94820906-fa27f100-03ce-11eb-92b6-b440f4c56112.png)





## STEP 2: Clone the Forked Repository
Go to the repository you just forked and clone it

```
git clone <forked-repo-url>
```

![Screenshot from 2020-10-01 10-21-52](https://user-images.githubusercontent.com/6632748/94821972-2c861e00-03d0-11eb-9904-5795398b1faf.png)




## STEP 3: Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd <forked-repo>
```

![Screenshot from 2020-09-30 11-58-40](https://user-images.githubusercontent.com/6632748/94822252-7111b980-03d0-11eb-95dc-6e90d1b9451d.png)

Now create a branch using the git checkout command:

```
git checkout -b <your-new-branch-name>
```

![Screenshot from 2020-09-30 12-07-15](https://user-images.githubusercontent.com/6632748/94822409-9e5e6780-03d0-11eb-87d6-3cf0dc4f7615.png)



## STEP 4: Make necessary changes and commit those changes

Now open Contributors.md file in a text editor, add your name and College/University to it, in the format 

```
[Jane Doe] [College/University]
```

![Screenshot from 2020-09-30 12-14-00](https://user-images.githubusercontent.com/6632748/94822586-d2398d00-03d0-11eb-8961-db3e556136b2.png)



Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.


```
git status
```

![Screenshot from 2020-09-30 12-20-27](https://user-images.githubusercontent.com/6632748/94823065-6ad00d00-03d1-11eb-892d-2cbc7472a220.png)



If you go to the project directory and execute the command git status, you'll see there are changes.

Add those changes to the branch you just created using the git add command:

```
git add Contributors.md
```

OR 

```
git add .
```

![Screenshot from 2020-09-30 12-20-38](https://user-images.githubusercontent.com/6632748/94823124-7f140a00-03d1-11eb-8df5-4622abee0039.png)





Now commit those changes using the git commit command:

```
git commit -m "Add <your-name> to Contributors list"
```


![Screenshot from 2020-09-30 12-20-47](https://user-images.githubusercontent.com/6632748/94823158-8affcc00-03d1-11eb-8528-14cdae611425.png)


## STEP 5: Push your changes to your forked repository

```
git push origin <name-of-branch>
```

![Screenshot from 2020-09-30 12-25-32](https://user-images.githubusercontent.com/6632748/94823287-aff43f00-03d1-11eb-95d1-7c05cc19f6c9.png)


## STEP 5: Submit your changes for review

If you go to your repository on GitHub, you'll see a Compare & pull request button. Click on that button.

![Screenshot from 2020-10-01 10-35-43](https://user-images.githubusercontent.com/6632748/94823496-eaf67280-03d1-11eb-8cc4-9f7bef468264.png)

![Screenshot from 2020-09-30 12-29-09](https://user-images.githubusercontent.com/6632748/94823378-c69a9600-03d1-11eb-8c82-0cab3c6d92c1.png)







