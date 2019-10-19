 # Basic Workflow
 The basic workflow on this magic draw project is described here.
 ## Getting started
 To start contributing navigate to the desired directory through your favourite terminal(i.e. [Git Bash](https://git-scm.com/downloads)):
 ```bash
 cd path/directory
 ```
 Then clone this repository using the command below:
 ```bash
 git clone https://github.com/MantasGra/ISPagrindai.git
 ```
The repository folder should appear in your desired directory navigate to it and continue work from there:
```bash
cd ISPagrindai
```
## Branching
Whenever working on any new additions to the project a seperate branch should be created. To do that run the following command:
```bash
git checkout -b name-of-my-branch
```
This creates the branch locally. To create a corresponding remote branch run:
```bash
git push --set-upstream origin name-of-my-branch
```
Doing this makes your subsequent push and pull command executions know what to do.

NOTE: Try and name your branches so that it would reflect what your changes are about(i.e. fix-this-and-that).

NOTE2: It's best if the branches are created from the latest version of the master branch. To ensure that you can run this sequence of commands:
```bash
git checkout master
git pull
```

## Committing
Usually all of your work will be done in the single .mdxml file. Once done save your work in the same format(.mdxml).
To make your changes appear in the remote repository a sequence of commands should be executed.
Assuming you have navigated to the repository folder you can run the following command to stage your changes for your next commit:
```bash
git add .
```
Once your changes are staged you can commit your changes by running:
```bash
git commit -m "Commit message"
```
The commit message should reflect changes made on that commit(i.e. "Fix this and that").
To push your commit to the remote repository just run the following command:
```bash
git push
```

## Pull requests
Once your work is done, please create a pull request on GitHub([this](https://help.github.com/en/articles/creating-a-pull-request) might help).
