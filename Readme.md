# Github Branch Lab

Some Notes:
* Steps 1 should only be done once by the project lead.
* Steps 2-3 done once by all contributors/teammates.
* Steps 4-10 done by all contributors/teammates.
* Steps 11 should only be done by the project lead.
* Steps 12 should be done by all contributors/teammates.

## The leader of the group should do the following: 
1.  Create a new repository in your organization.

</br>

11. merge the changes


## All memebrs should do the following:
2. Fork
3. Clone `git clone FORKED_REPO_URL`
4. Add upstream as a remote repository
   - `git remote -v `
   - `git remote add upstream Organization_URL` (Organization_URL = The Organization repo link)
   - `git remote -v` you should see 2 origin and 2 upstream remotes 
5. Create and checkout to a new feature branch
    - `git checkout -b Feature_Name`
6. Add html file that has `<h1>Hello from YOUR_NAME</h1>`
7. Add your work to the staging area `git add .`
8. Save the staged changes via commit `git commit -m “”`
9. Push the new branch to origin `git push -u origin Feature_Name`
10. Submit pull request

</br>

12. Update the local master by pulling changes from Upstream master `pull upstream master`
