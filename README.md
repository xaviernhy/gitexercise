# gitexercise
git exercise on week 3

Git Exercise
Simulate the following process using GitHub and Codespaces.
1. Create a New Repository:
1. This repository includes a simple Python program (e.g., a script that prints a message) in the main branch.
2. Alice Creates and Works on Branch A:
1. The repository is cloned to the local machine of Alice.
2. Alice creates Branch A locally and checks out to that branch. She modifies the Python program by introducing a syntax error (e.g., a missing closing 
parenthesis in a function call). Alice commits these changes locally.
3. Bob Works on Branch B:
1. Bob creates Branch B from the main branch on GitHub.
2. He modifies the same Python program in a way that will cause a merge conflict with Alice's changes in Branch A.
3. His change is merged to the main branch in GitHub.
4. Alice Pushes Changes and Creates a Pull Request:
1. Alice pushes the changes in Branch A to GitHub and creates a pull request for these changes.
5. Carol Reviews the Pull Request and Requests Code Fixes:
1. Carol, the senior team member, reviews the pull request and requests Alice to fix the syntax error and merge conflict.
6. Alice Fixes Syntax Error and Merge Conflict:
1. Alice switches to Branch A, resolves the merge conflict, and fixes the syntax error locally.
2. She then pushes these changes to GitHub to update the pull request.
7. Carol (the Senior Team Member) Reviews and Merges the Changes:
1. Carol reviews Bob's pull request on GitHub. After ensuring everything is in order, she accepts the pull request and merges the changes from Branch B into 
the main branch.
At the end of this exercise, capture a screenshot of the Commit graph using the Git History extension in VSCode (You should show all the local branches 
and remote branches) 
