# DIO Git/GitHub Challenge

Welcome to the DIO Git/GitHub Challenge! This project is designed to enhance your understanding of Git and GitHub, the dynamic duo of version control and code hosting. Whether you're a seasoned developer or just starting, this challenge is a fantastic opportunity to deepen your knowledge.

## About Git

Git is more than just GitHub! It's a powerful version control tool that empowers developers to track changes, collaborate efficiently, and manage project history. While GitHub is a popular platform for hosting code using Git, it's essential to explore other code hubs such as GitLab and Bitbucket. Expand your horizons and discover the vast landscape of version control.

### Resources to Master Git

- [Official Git Documentation](https://git-scm.com/doc)
- [Microsoft's Git Guide](https://learn.microsoft.com/pt-br/devops/develop/git/what-is-git)
- [Atlassian's Git Tutorials](https://www.atlassian.com/git/tutorials/what-is-git)
- [W3Schools Git Introduction](https://www.w3schools.com/git/git_intro.asp?remote=github)

## SSH Authentication

Ensure the security of your code hub account by setting up SSH Authentication. This adds an extra layer of protection, allowing you to clone private repositories and push changes securely using SSH keys.

### What is SSH?

SSH (Secure Shell) is a cryptographic network protocol for secure data communication. Learn more about it [here](https://www.techtarget.com/searchsecurity/definition/Secure-Shell).

### Setup SSH for Your Code Hub

- [GitHub SSH Setup](https://docs.github.com/pt/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
- [GitLab SSH Setup](https://docs.gitlab.com/ee/user/ssh.html)
- [BitBucket SSH Setup](https://bitbucket.org/account/settings/ssh-keys/)

## Pro Tips and Tricks

Enhance your Git experience with these handy commands and tips:

- **GitHub Online Editor:** Press '.' on GitHub to enter the online editor directly.
- **Gitkeep Magic:** Create a ".gitkeep" file in a folder to force Git to recognize the folder.
- **Amend Git Comment:** Change your last commit comment using `git commit --amend -m "new git comment"`.
- **Resetting Commits:** Use `git reset` to undo commits selectively based on their hash.
  - `--soft`: Keeps changes in the staging area.
  - `--mixed`: Default, adds changes to tracked files.
  - `--hard`: Deletes changes directly.
- **Remove from Tracking:** Untrack changes with `git restore <filename>`.
- **Clone Specific Branch:** Clone only a branch with `git clone -b branch_name --single-branch <repository_url>`.
  - Example: `git clone -b develop --single-branch https://github.com/PSRadavelli/webpack-study`

## Stash It for Later

Stash your code changes for future use, especially after merges or similar operations.

- Save changes with `git stash`.
- View stashed changes with `git stash list`.
- Apply stashed changes with `git stash apply`.
- Apply from a specific stash index using `git stash apply stash@{0}`.
- Apply and remove from the list with `git stash pop stash@{0}`.

Happy coding, and may your Git journey be smooth and productive! 🚀✨
