# git_assignment_HeroVired
Q.2: For a project that deals with large binary files, integrate Git LFS (Large File Storage) to handle these files efficiently. Demonstrate how to add, commit, and push binary files to the repository, ensuring they are tracked by Git LFS correctly. Clone the repository on another machine to verify that the binary files are downloaded correctly.

In the repository ‘git_assignment_HeroVired’, create a branch ‘lfs’. Upload any large file whose size is over ‘200mb’ and try to push this file into the repository.

Performed below steps:
-Download and install git lfs for windows.
-Created new branch called 'lfs' in git repository called 'git_assignment_HeroVired'.
-Run command git lfs install.
-Verify lfs version.
-Track .zip extention files using command got lfs track "*.zip"
-After running above command .gotattribute file generated.
-Added more than 200 MB size file in local repo and pushed it to lfs branch.
-Clone repository 'git_assignment_HeroVired'. using command git clone -b lfs repo_url in different location and pulled all data from lfs branch.
-Able to pull successfully large file from remote which having size more than 200 MB size.

