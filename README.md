# firstContributions
This repo allows Open Source beginners to learn how to contribute to Open Source Projects on Github!

Inspired by https://github.com/firstcontributions/first-contributions, this repo provides a smaller version of this project for the Red Hat BUILD event. 

Follow these steps to create your first contribution!


## STEP 1: Fork the Repository
At the top right corner of this github repository, click the "Fork" button.


## STEP 2: Clone the Forked Repository
Go to the repository you just forked and clone it

```
git clone forked-repo-url
```

## STEP 3: Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd forked-repo
```

Now create a branch using the git checkout command:

```
git checkout -b your-new-branch-name
```

For example:

```
git checkout -b first-contribution-repo
```

## STEP 4: Make necessary changes and commit those changes

Now open Contributors.md file in a text editor, add your name and College/University to it, in the format 

```
[Jane Doe] [University]
Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.
```

```
git status
```

If you go to the project directory and execute the command git status, you'll see there are changes.

Add those changes to the branch you just created using the git add command:

```
git add Contributors.md
```

Now commit those changes using the git commit command:

```
git commit -m "Add <your-name> to Contributors list"
```


## STEP 5: Submit your changes for review

If you go to your repository on GitHub, you'll see a Compare & pull request button. Click on that button.


```
Now submit the pull request.
```







