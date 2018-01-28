# 100 Days Of Code - Log

**Links(s) to work:** https://www.freecodecamp.org/challenges/learn-how-freecodecamp-works

### Day 1: Jan 6, 2018

**Today's Progress**: 
1. Reviewed Git and GitHub Video: https://www.youtube.com/watch?v=Z9fIBT2NBGY
2. Setup Git repository
3. Downloaded Sublime and watched a video on Sublime: https://www.youtube.com/watch?v=SVkR1ZkNusI

**Key Links**:
  - Git: https://git-scm.com/
  - Git Syntax: https://help.github.com/articles/basic-writing-and-formatting-syntax/

**Configuring Git**:
1. Download Git from the link given above.
2. Configure Git:
  - git config --global user.name "Name"
  - git config --global user.email "Your E-Mail Address"
    
Create a directory where you want your source code to be stored. Initialize the Git repository to point to that directory.
  - cd \<directory>
  - git init
 
**Commonly used Git Commads**
  - git status
  - git diff \<filename> - shows what changed in the file since last commit
  - git add \<file that has been modified>
  - git commit --message "message why the code was changed" OR git commit -m "message why the code was changed"
  
  - git log - shows log of commits
  - git branch \<branch name>: Create a new branch
  
 ### Day 2: Jan 7, 2018
 **Working with remote**
  - git remote -v : See the status of what is stored on the remote repository
  - git remote add \<local repository> \<git project URL on remote>. For example
    - git remote add origin https://github.com/neerajs/git-101.git
    
  - git push \<remote> \<branch> : Push your code to remote repository. For example: git push -u origin master
  - git pull \<remote> \<branch> : Pull code from remote repository

### Day 3: Jan 27, 2018
*** CSS ***
Here's an example CSS class declaration:
<style>
    .blue-text { color: blue;
    }
  
  p { font-size:16px
  }
\</style>

**Using Inline classes**
\<h2 class="blue-text">
  CatPhotoApp
\</h2>

