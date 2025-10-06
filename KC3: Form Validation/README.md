> ⚠️ Clone this repo into your `techtonica-knowledge-checks` folder and push your changes there, [see demo](https://www.dropbox.com/scl/fi/hg39hhze34487jgrae15w/Move-Knowledge-Check-into-Private-Repo.gif?rlkey=nv9b29p5rvflecqaa1ok7dwb6&st=0b9wfaup&dl=0). Be sure to add the appropriate staff contributors. Before you are able to push your changes to your new private repository you will need to "uninitialize git" repository in the __**cloned root directory**__ `rm -rf .git`. 
> 
> If you want to create a new private repo instead of pushing into your `techtonica-knowledge-checks` folder, you will need to then reinitialize to your new repo.
> ```
> git init
> git add .
> git commit -m "Initial commit"
> git remote add origin <remote-repository-url>
> git push -u origin <your-branch-name>
> ```

# JavaScript Form Validation & Error Handling

### Tasks

1. Print a message inside the `div` with the error class whenever the user submits a blank form  (JS)
2. Handle failure icon visibility (CSS). Hint: check the HTML for the error-classes
3. Handle the success icon visibility if a user completes all inputs and submits (CSS)
4. Ensure password must have more that 8 letters
5. Email can not be empty

### Bonus

* Change the success/failure icons according to successful input values or incorrect input values
