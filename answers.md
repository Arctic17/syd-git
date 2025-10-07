# Answers of Louis Rowlings Arctic17 

## Basics
### Task 1
To start the the the file is unchanged meaning that there have been no modification to the file since the last pull. 
Once the file is saved with the modification its statuse changes to "unstaged". This indecates that the file is modified but has yet to be placed on the next commit. An analogy for this would be that the letter has been writen but has yet to be given to the post office hence it will not go on the next train out.

### Task 2
1. The exaple commit message can be broken down "CHG: " defining what the commit is doing in this case changing of data. then comes what was changed "personal data" in this case. Finaly where the changes would take place in this case that would be "answer.md".
2. No in the case of this Lab it is not possible to commit without a message as messages are the best way to keep track of changes and modification on a project. However it is possible to disable this lock on cetrain Repos using a command unknown to me.
3. The commit changes my local repository with the updated changes to the files i have just commited. how ever this does not affect the online/remote repos untile a git puch is executed 
4. No as stated in the previeus answnser the online repo has not changed unitl a git push.


### Task 3
I can see that ther are 2 typs of files waiting to be staged the first being the "answers.md" the second being the new **Untracked** "README.md". The README file is untracked as it has just been created. The untracked means that the file has yet to be part of a commit and start having its modification tracked by git.

### Task 4
As Checkout Commit is selected the files fond on the file explorer ar reset to theire intitial commit state meaning that there are no README.md and the answers.md is empty as they when wht the repo was cloned. when going back to the last commit the file exlporer goes back to is latest state with all of the lates saved file from that commit.

### Task 5
The diffrence between the local repository and the remote repository is that the local repository is updated every commit and is the basis on which the user devlopes on. On the other hand the remote repository it a repo that can be accesed by many and can only be modified througha puch and is the amalgamation of all pushes. 
If the local repository would be deleted only the local modification will be affected. this means any modifications done after the last Git push will be erased as they when only found on the local repo and not on the remote repo.

### Task 6
Nothing has happend to it as the repo was cloned localy by the user and has not be modified. this means that the original repos was used as a base for the current version but bairs no link until a pull request is made to rejoin it to the original 

## Gitgraph

### Task 7
![Gitgraph](img/gitgraph.svg)
1. Branch 
2. Commit Hash
3. Commit Message
4. User that commited/merged/Branched
5. Version of main 
6. latest commite made to develop
7. feature of user authentication branched of main and merged into the develop branch
8. current state of the merge (Version that the client recieves)
9. Development branch
10. Main time line