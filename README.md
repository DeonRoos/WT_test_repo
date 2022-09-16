# WT_test_repo

Repo to test version control within department work structure and flow.

# Features to test

* Clone into existing repo

* Pull updates from repo

* Commit changes

* Push changes

* Merge conflicts

* Forking and branching a repo

* Pull requests to merge branches

## Sugessted folder structure

If we do make use of git for projects, then having a standardised folder structure may improve accessibility.

For instance, we could use:

* Project folder (e.g. AAAA0001)

  + Analysis folder 
  
    - folder which contains the final simulation or statistical analysis
  
  + Data processing folder 
  
    - folder which contains all data processing steps to achieve data ready for analysis
  
  + QA folder 
  
    - folder which contains Susie's QA form
  
  + Unit testing folder 
  
    - folder which contains all QA/unit testing scripts that ensure components of work are robust
  
  + Output folder 
  
    - folder which contains all produced outputs, e.g. figures, results, anything that may be included in the final document
  
  + Data folder 
  
    - folder which contains both the master data and any processed data
  
  + Read me file 
  
    - file which includes a brief overview of repository [may just be summary from QA form]
    
# Terminology

`Commit`: Commit a locally saved version of a document, ready to be uploaded to the repository.

`Push`: Upload, or "push", the commited local save to the repository.

`Pull`: Download, or "pull", the most recent version of the repository to your local machine.

`Branch`: Create an experimental copy of the repository to test, or change, some aspect of the code.

`Pull request`: Request that the experimental branch is merged with the main branch.

`Fork`: Create an entirely new version of the repository that will be distinct from the main branch (e.g. use the boar IBM as the template for a deer IBM)

# Suggested work flow

Once a main branch (i.e. repository) has been created, each team member would then work in their own, self-contained, branch. Within a given branch, the individual team member can make any changes they deem necessary. Once the team member has a version of the code they wish to make the new main branch, they can submit a pull request to the repository owner. The repository owner is then tasked with merging any branches with the main branch, once a team member has submitted a pull request. This, ideally, reduces any potential merge conflicts.

In this way, the coding occurs in a hierarchical nature, with the main branch being at the top and each team member's version of the branch being one level lower. 

A given team members branch will be a self-contained version of the main branch. Any changes can simply be commited and pushed at the users desire. Once the team member is happy with their version of the branch and believe it should be merged with the main branch, then they can submit a pull request.

Within a given branch, the general rile is commit often, but push (or pull request) infrequently. Each commit is treated as a version control, therefore any small changes can be reverted to. As such, if commits are infrequent, then multiple changes may have been made, meaning version control is less useful.