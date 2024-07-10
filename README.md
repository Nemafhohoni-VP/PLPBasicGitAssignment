Steps taken to set-up a repository remotely and locally, making changes, committing and pushing the changes thereof

1. Repository Set-up:
   
I logged into my GitHub Account and created a new repository
 on the tab labelled "new" and called the repository "PLPBasicGitAssignment".

I then initialized the repository with a README file by clicking the checkbox.

And created the repository on the tab labelled "create repository". 


2. Local Setup:

I then created a new folder on my local machine and named it "PLPBasicGitAssignment".

I then opened the terminal or and navigated to the folder I had just created created by using the following command:
cd "C:\Users\Vhukhudo\Videos\Coding\Software Engineering\PLPBasicGitAssignment"


3. Git Initialization:

I then initialized a new Git repository in my local folder by using the command git init.


4. Connecting to GitHub:

I then linked my local repository to the GitHub repository I created initially in step 1 by using the following command:

git remote add origin https://github.com/Nemafhohoni-VP/PLPBasicGitAssignment.git


5. Making Changes:

Inside my local folder "PLPBasicGitAssignment", I created a new text file and named it `hello.txt`.

In addition, I added a simple text message "Hello, Git!" inside the hello.txt file I had just created.


I then tracked the changes made in the hello.txt file by using the following command: 
git add hello.txt

I then committed the changes made by using the following code:
git commit -m "Add hello.txt with a greeting"


6. Pushing to GitHub:

I then pushed the committed changes to the remote repository using the following command:

   git push -u origin main


7. Verification:

I visiited the repository I had initially created to confirm and verify that the  `hello.txt` file and commit message were visible. And they were.

Additional
I then amended the README.md file. I detailed the steps I took to set-up a local and remote repository, make changes to the repository, commit the changes and finally push the changes to GitHub in it.

I then tracked thoses changes, committed the changes and pushed the changes to GitHub

                                       THE END      
