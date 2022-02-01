# Github submission instructions

We will use the fork and pull request workflow for submissions in this class. The idea is that you will make the required changes in your own copy, and then submit a pull request and @mention me (@rivlev). __The pull request and @mention comprise your submission for this assignment.__

## Getting started with Github

1. If git is not installed on your computer, download it [here](https://git-scm.com/downloads).
2. Create a Github account.
3. Generate a **personal access token** (instructions [here](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)). Give it full repo and user permission. Copy paste it somewhere so you don't lose it.


## Getting started with an assignment

Github Classroom will create a *remote* repository for you that is seeded with startup code. First, *clone* the repository to make a local copy on your own machine. You will make changes to the code on your own computer and sync between the local and remote copies.

1. In a terminal or command prompt window, navigate to the directory where you want to keep the repository. Since you will be creating multiple repositories for this class, you may want to organize them in a directory structure such as cisc3620/labs/.

2. From the online github repository page, copy the url of your repository. You can get it from the green "clone or download" button near the top right of the window.

3. In the terminal, do

   ```git clone --recursive <THE_URL_YOU_COPIED>```
   
* If you get the error message "Command not recognized", that means you don't have git installed on your machine. You can download it from [here](https://git-scm.com/downloads)
* If it prompts you to log in, enter your Github username and paste in your personal access token.

4. Change directories so you are in the git repository (e.g. ```cd 0-get-started-rivlev```)

## Branch

__Before__ you make any changes, create and switch to a new branch

```git checkout -b hw```

This will make sure the original master branch stays clean, so you can merge back into it with the pull request and have the differences all apparent in one place.

## Modify

Edit the project files to fulfill the assignment requirements.

## Ask for help

If you are running into difficulty with your project you can ask for help by opening an issue  and @mentioning me (@rivlev). Please note that full-scale debugging or code review can only happen during office hours.

## Stage your files

From the top level of the repository:

```git add doc1 doc2 doc3```

(for all files you have modified).

This prepares these files to be included in the next ```git commit```. Make sure to do this *after* you've made the changes you want to save. Make sure to only add code files and not project files.

## Commit changes

```git commit -m "message"```

This records a snapshot of the changes you've made. Make sure to include a meaningful message so you know what this update was for.

## Push your changes to the remote repository

```git push origin hw```

## Create a pull request

Go back to your Github repository page. Click "New pull request". "Base" should be "master" (the branch you want to make changes to), "Compare" should be "hw" (the branch with the changes you want to make).

You should see a preview of the changes you made (called a "diff").

Click "Create pull request". 

In the subject line, write a tiny summary of your changes. In the body, fill out the pull request template. Make sure it includes your name and @rivlev. 

Click "Create pull request". This will notify me of your submission.

## Do not press the big green "Merge" button!
This will close your pull request.
