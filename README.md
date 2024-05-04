# git_assignment_HeroVired
Q.1: You are part of a development team working on a Python application called "CalculatorPlus." The application provides basic arithmetic operations, such as addition, subtraction, multiplication, and division. Your task is to implement a new feature that adds support for calculating the square root of a number.

Performed below steps:

-Created new repository called 'git_assignment_HeroVired in github account.
-While creating repository add README.md file in main branch.
-Created new branch called 'dev'.
-Implemented a new feature that adds support for calculating the square root of a number with given existing code and added it to dev branch.
-Merged dev brach changes into main branch and released of version 1 of the ‘calculator plus app’.
-Added one collabrator to my repository to review my code.
-Created new branch called 'feature_sqrt'.
-Added squr_root code to this branch.
-Switched back to the ‘dev’ branch.
-Made fixes for divide function in 'dev'.
-Make sure and keep same changes in 'feature_sqrt' branch.
-Create pull request from dev branch to main branch.
-While creating pull request added reviewer as addedd collabrator and send request for code approval.
-Collbrator review code and suggested few things in code.
-As per suggestion made necessory changes in code and submitted request again for code approval.
-This time code looked better and collabrator approved code changes.
-Confirm merge changes and submitted.
-Dev branch changes merged successfully into main branch.
-Merged feature_Sqrt branch changes with dev branch.
-Again merge final changes from dev branch to main branch and release of version 2 of the ‘calculator plus app’.

***************************************************************************************************************************************************************************************

Q.2: For a project that deals with large binary files, integrate Git LFS (Large File Storage) to handle these files efficiently. Demonstrate how to add, commit, and push binary files to the repository, ensuring they are tracked by Git LFS correctly. Clone the repository on another machine to verify that the binary files are downloaded correctly.
In the repository ‘git_assignment_HeroVired’, create a branch ‘lfs’. Upload any large file whose size is over ‘200mb’ and try to push this file into the repository.

Performed below steps: 

-Download and install git lfs for windows. -Created new branch called 'lfs' in git repository called 'git_assignment_HeroVired'.
-Run command git lfs install.
-Verify lfs version. -Track .zip extention files using command got lfs track "*.zip". 
-After running above command .gotattribute file generated.
-Added more than 200 MB size file in local repo and pushed it to lfs branch.
-Clone repository 'git_assignment_HeroVired'. using command git clone -b lfs repo_url in different location and pulled all data from lfs branch.
-Able to pull successfully large file from remote which having size more than 200 MB size.

***************************************************************************************************************************************************************************************

Q.3: In this same GitHub repository, create a new branch ‘geometry-calculator’, we'll work on a simple Python program that calculates the area of a circle and the area of a rectangle. We'll use Git stash to switch between working on multiple features (calculating circle area and calculating rectangle area) without committing incomplete changes.

Performed below steps:

-Created new branch called 'geometry-calculator'.
-Implemented a new feature a simple Python program that calculates the area of a circle and the area of a rectangle.
-Created new branch called 'feature_circle_area'.
-Implemnted code to call function 'calculate_rectangle_area' by passing radius as parameter.
-Stash the changes.
-Created new branch called 'feature_rectangle_area'.
-Implemnted code to call function 'calculate_rectangle_area' by passing length and width as parameter.
-Stash the changes.
-Switch back to branch feature_circle_area.
-Pop stash changes.
-Code changes commit and push to branch feature_circle_area on repo.
-Switch back to branch feature_rectangle_area.
-Pop stash changes.
-Code changes commit and push to branch feature_rectangle_area on repo.
-Added Collabrator on repo for code review.
-Create pull request with collabrator as reviewer for branch feature_circle_area to merge code into geometry-calculator branch.
-Collabrator review changes and approve changes.
-After getting approval merge changes.
-Create pull request with collabrator as reviewer for branch feature_rectangle_area to merge code into geometry-calculator branch.
-Collabrator review changes and approve changes.
-After getting approval merge changes.
-Finally merge geometry-calculator branch changes into main branch.

***************************************************************************************************************************************************************************************



