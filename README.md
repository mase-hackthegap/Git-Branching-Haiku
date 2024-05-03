
3. **Adding Your Haiku:**
   Navigate to the `POEM.md` file within your repository. Look for the section titled **"Add your poem here"**. You will add each line of your haiku in the designated branches:
   - In the `feature-line-one` branch, add the first line of your haiku.
   - In the `feature-line-two` branch, add the second line of your haiku on the new line directly below where the first line of your poem was. Do not add your first line of your poem here.
   - In the `feature-line-three` branch, add the third line of your haiku on the new line directly below where the second line of your poem was. Do not add your first or second line of your poem here.

4. **Committing Your Changes:**
   As you complete each line in its respective branch, make sure to:
   - Run `git add .` to stage your changes.
   - Commit the changes with a meaningful message using `git commit -m "Add first/second/third line of haiku"`.
   - Push your changes to the remote repository with `git push feature-line-one`, `git push feature-line-two`, and `git push feature-line-three` respectively.

### Part 2: Merging Branches into Main

1. **Prepare for Merging:**
   Make sure your local main branch is up to date by running `git checkout main` followed by `git pull main`.

2. **Merging the Branches:**
   - Switch to the main branch: `git checkout main`.
   - Merge each feature branch into the main branch one at a time using the following commands:
     - `git merge --no-ff feature-line-one` - This merges the first line of your haiku.
     - `git merge --no-ff feature-line-two` - This merges the second line of your haiku.
     - `git merge --no-ff feature-line-three` - This merges the third line of your haiku.
   - If there are any conflicts, resolve them before finalizing the merge.

5. **Submission:**
   Once you have completed adding lines to all branches and have merged them into the main branch, ensure all changes are pushed to your forked repository. Submit the link to your repository for evaluation.
