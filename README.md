# Hello-World
Learning GitHub and linking to my RStudio! 
Now I can add more details about my repository as I learn the basic instructions. 

These further edits are to demonstrate how branches work - create a copy of the main branch, and allow me to make changes in here that do not affect the main branch. 
Apparently, the new edits are called commits. 

To connect this repo to RStudio, I copied the repo URL and pasted it in the Git slot after creating a new project with version control in RStudio. The new project automatically took the name of the repo and downloaded the file(s) i.e. this .md file, that was in my repo for viewing within RStudio.

To save changes, click on the Git tab in the environment; Diff highlights changes and Commit opens the tab to save the changes. Click "Staged" an commit changes. These are local to the RStudio repo. 

To sync the repo in RStudio and that in the online repo, use the green arrow/Push button. This should upload changes to the online repo. 

Lastly, these changes can be saved to the original branch or a new branch, which can later be merged using a pull request. Branches are created using the branch icon or main pulldown menu in the Git tab. 

Pushing changes to the online repo sometimes prompts for username and password, which can be avoided by using a PAT - personal access token - generated through GitHub and stored in R using the credentials packages. Hopefully, it should no longer ask for passwords when saving and syncing. 