# Codeowners Demo Repository

## Description
This repository demonstrates how a CODEOWNERS file can be used to prevent users from merging a PR that changes specific files. The CODEOWNERS file specifies specific files and directories that are protected and what teams or users can approve PRs. 

## How to use
* Clone this repository and edit `.github/CODEOWNERS`. 
* Modify, add or delete additional entries that match specific files you need protected. 
* When a user submits a PR that modifies or deletes one of these files, the CODEOWNERS file will be referenced and request PR reviews by the users mentioned on the line that matches the file being modified.

## Why?
In an Enterprise organization, a central DevX team, security team, ops team or whomever may need to limit who can change workflow files. They can implement this pattern on the files under `.github` and require that the team be required to review changes to any of the files under that directory.

## Additional Resources
* [GitHub CodeOwners documentation](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners)
