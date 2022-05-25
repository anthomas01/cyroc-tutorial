### cyroc-tutorial

1. Fork this repository, using the button in the upper right corner of your screen.
2. Clone your fork to your computer and enter the directory using the git bash terminal
    - `git clone https://github.com/your_git_repo.git filename && cd filename`
4. Create a branch with the title set as your isu netid (ex: jdoe)
    - `git branch jdoe && git checkout jdoe`
6. Once the branch is entered, create a text file named as your **firstname_lastname** in the cloned folder
8. In that text file, tell a little about yourself. Name, year, major, strongest programming language, what is your specific interest in analysis/optimization, and maybe a fun fact
9. Add the original repo as the upstream 
    - `git remote add upstream https://github.com/anthomas/cyroc-tutorial.git`, now we will call the original repo "upstream"
    - Once done use `git remote` to verify the upstream is added
    - You should see output like this:  `upstream origin`
11. Commit your changes and push to your fork
    - `git add .`
    - `git commit -m "your commit message"`
    - `git pull upstream origin`
    - `git push`
12. Merge your netid branch to your main branch, but do not delete the netid branch
12. Fetch upstream to get the latest changes to main repository
13. Make a pull request to merge your fork to main repository

Basic Github command list is available here: [GitHub Command List](https://github.com/anthomas01/notes/blob/master/README.md#basic-commands)
