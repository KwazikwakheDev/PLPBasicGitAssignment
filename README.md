# PLPBasicGitAssignment

## Steps
  1. **Step 1**: **Repository Setup**
  - I created a github repository and Initialized it with a README file which caused the Branch  to be main.

  2. **Step 2**: **Local Folder Setup**
  - Was to create the a new folder with name **PLPBasicGitAssignment**
  - I created this folder using Gitbash or Git, using the command >> mkdir
  - After i navigated to it with the command >> cd.

  3. **Step 3**: **Git Initialization**
  - when you inside the folder using the command >> cd
  - Initialize the repository using >> git init

  4. **Step 4**: **Connecting To GitHub**
  - To connect my local folder or repository created in step 1
  - Use the command >> git remote add origin "repository-url" replace the url with Github repository
  5. **Step 5**: **Making changes and creating the file**
  - Inside the local folder create a hello.txt file with text in it.
  - To do that use the command >> echo "Text or Your message" > hello.txt

  6.  **Step 6** : **Committing Changes**
  - Stage the changes with >> git add  hello.txt
  - commit the changes with >> git commit -m "Your commit message"
  - After push the changes to github using the command >> git push -u origin main

  7. **Step 7** : **Verification**
  - To verify changes log in to Github on your web browser and confirm that there is the commit message and the hello.txt file with it content.

  **Problems faced and the solution**
  - The problem is that when you create a repository in github and initialize it with the README, it makes the branch main.
  - So i was working in the master branch in Git so whenever i pushed changes i didn't see them.
  - To debug that i checked where i am with the command >> git branch
  - And then i used the command >> git checkout main 
  - This command helped me to switch from the master to main branch
  - And then I repeated the steps, after pushing i was able to see the changes. 

  :smile:
  

