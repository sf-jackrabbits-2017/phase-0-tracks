# Git Definitions

**Instructions: ** Define each of the following Git concepts.

* What is version control?  Why is it useful?
Version control is a system by which a programmer can keep track of changes made to a pieces of code while ensuring the original source code is protected from unwanted edits. 
It is useful because it not only provides a safeguard to your master branch of code, but it also allows for other collaborators to work on the same piece of code without stepping on each others toes saince they each have their own independent copies to work on and can merge in later when ready.

* What is a branch and why would you use one?
A branch is a copy of the source code that can be used to add specific features or make modifications without fear of disrupting or exposing source code to problems. It also allows you to work and share (once pulled) specific features that can be individually edited or updated as needed. 

* What is a commit? What makes a good commit message?
a commit is the action of confirming changes or modifications to branches. It records these changes to your local repository which basically means it saves them. A good commit message is one that clearly explains what edits or changes have been made as a result of this commit. It should be clear enough that any developer can look at the commit message and understand the purpose of the commit.

* What is a merge conflict?
A merge conflict is an error when one branch attempts to merge into another but there is a conflict between the two that must first be resolved. A example of this is when data from the master branch has been edited and the branch files tries to merge using the old data. They occur when descepencies exist in which git does not clearly know how to resolve them and must be told what to do (or edit the branches so there is no longer a conflict).