1. How do I create a new branch in Git?
   git branch <branch-name>

2. How do I switch branches in Git?
   git checkout <branch-name>

3. How do I push changes to a remote repository?
   git add .
   git commit -m "your-commit"
   git push

4. Write a script that will take a list of files and move them to a new branch.

   # create a new branch

   git checkout -b branch_name

   # remove all files for this branch

   git rm -rf .

   # retrieve some files from master branch

   git checkout master -- file1 file2 file3 file4

   # commit changes

   git commit -m "create new branch with some file"

5. Write a script that will clone a remote repository and checkout a specific branch.
   git clone <remote-repository-url>
   git checkout -b <branch-name>

6. Write a script that will compare two different branches and list the differences in their contents.
   git diff <branch1> <branch2>

7. Create a script that will list all commits made by a specific user.
   git log --author="<username>"
