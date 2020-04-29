# Python and Git practice.
## Git - What is git?
Git is a version control system! What does that mean and how does it help?  
- It means that it is a tool that allows you to save different versions of your code, without saving duplicate copies of it.  
- It keeps track of changes that you make to different files in your repository and you can save (commit) the current status of your code for future backtracking.  
- It also gives you the ability to save this code in a common remote repository (same as uploading to google drive), where you can share it with other people. This process is called 'Pushing'.  
- Similarly you can download the code from this remote repository to your local repository. (Pulling)  
- There are several important git commands that we would be practicing, so that you get familiarized with the basic workings of git.  

To start, download and install Git Bash in your Windows machine. You can find it in [Download Git](https://git-scm.com/download/win)  
Follow the instructions in [Git Installation](https://www.stanleyulili.com/git/how-to-install-git-bash-on-windows), making sure that in step 8, you select the following instead.
  In STEP 8 “Git from the command line and also from 3rd-party software”  
  
Once you have git set up, download and install Anaconda.

## Anaconda - What is it?  
Anaconda is a free and open-source distribution of the programming languages Python and R. The distribution comes with the Python interpreter and various packages related to machine learning and data science.  
Basically, the idea behind Anaconda is to make it easy for people interested in those fields to install all (or most) of the packages needed with a single installation. 

To start, make sure, you have installed Anaconda on your laptop! You can find it in [Download Anaconda](https://www.anaconda.com/distribution/#download-section). Follow the steps in [Anaconda Installation](https://www.datacamp.com/community/tutorials/installing-anaconda-windows), making sure you follow them for Python 3.7 instead. 

## Next Steps -
First, open git bash and clone the repository and save it on your local machine.
git clone https://github.com/israni/python_and_git.git

Here are some useful git commands that you would require.
1. git status  
Tells you the current status of the repository.

2. git pull  
Fetches and merges changes from the remote repository to the local repository.

3. git add <Filename>     
   OR to add everything   
   git add .
Stages the changes to be committed
    
4. git commit -m "Mention the Change"

5. git push
    


