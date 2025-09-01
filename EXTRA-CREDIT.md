## Extra Credit

question 1:
The --recursive flag is specified when initially cloning a Git repository if that repository contains submodules.
When you clone a repository with git clone, Git only clones the main repository. If that main repository references other Git repositories as submodules, those submodule directories will be created but will remain empty.
The --recursive flag instructs git clone to not only clone the main repository but also to automatically initialize and update all submodules contained within it. 
This ensures that the complete project structure is downloaded and ready for use in one command.

question 2:
