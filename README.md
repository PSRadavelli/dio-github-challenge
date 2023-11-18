#  DIO Git/GitHub Challenge

## Esta descricao tambem esta disponivel em [Português](https://github.com/PSRadavelli/dio-github-challenge/blob/develop/READMEpt-br.md)


Dio challenge project about Git/Github

References to get informed about git:

Be wise! Git doesn't mean only GitHub, Git is a version control tool, and GitHub is a website for hosting code that utilizes the Git tool, there are many different code hubs all over the internet such as GitLab and BitBucket

https://git-scm.com/doc

https://learn.microsoft.com/pt-br/devops/develop/git/what-is-git

https://www.atlassian.com/git/tutorials/what-is-git

https://www.w3schools.com/git/git_intro.asp?remote=github



## SSH Authentication
After your sign-up in a Code hub it's interesting, security wise, to add a SSH Authentication to your account, so only with this key you can clone your private repositories and push with your profile authenticated with SSH security.

What is SSH: https://www.techtarget.com/searchsecurity/definition/Secure-Shell

Github SSH: https://docs.github.com/pt/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

GitLab SSH: https://docs.gitlab.com/ee/user/ssh.html

BitBucket SSH: https://bitbucket.org/account/settings/ssh-keys/

## Some useful commands and information

> You can press '.' on GitHub to enter the online GitHub editor
> 

> if you create a ".gitkeep" file inside a folder makes git force recognize the folder.
> 

## change git comment with amend

`git commit --amend -m "new git comment"`
if you dont add the '-m "comment" ' suffix it enters the VIM editor mode so you can edit it

## Resetting commits

get commit hash by `git log` command

`git reset --soft <commithash>` removes the posterior commits and add it to the staging area

`git reset --mixed <commithash>` the default git reset command, it adds to our tracked files the posterior commits

`git reset --hard <commithash>` deletes all the posterior commit files directly

## Remove from tracking

`git restore <filename>`   

## clone only a branch from repository

`git clone -b branch_name --single-branch <repository_url>`

example:

`git clone -b develop --single-branch https://github.com/PSRadavelli/webpack-study`

`git stash apply` so you can save the differences in the branch for a posterior use
