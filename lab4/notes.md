Q1.  
--global means the setting applies to all repositories on your computer. Without it, the name/email would only apply to the current repository.

Q2.  
ls -a shows hidden files, including the .git folder. Inside .git are all the metadata and history Git uses to track changes.

Q3.  
Git offered to track all files in the folder. Some of them (like .venv/) are auto-generated and not written by me.

Q4.  
After adding .gitignore, the thousands of .venv files disappeared from git status. Only the files I actually care about remain.

Q5.  
.gitignore itself should be committed because it tells collaborators what to ignore. If it were ignored, everyone else would have to recreate it manually.

Q6.  
README.md moved from “Untracked files” to “Changes to be committed.” In the three-places model, it went from the working directory into the staging area.

Q7.  
Git printed a commit message summary and showed how many files were changed. It listed the number of insertions and which files were created.

Q8.  s
The first seven characters are the commit hash. They uniquely identify that commit so you can refer back to it later.

Q9.  
The four steps are: edit a file, stage it with git add, commit it with git commit, and repeat. That’s the cycle you did twice.

Q10.  
README.md is special because GitHub shows it on the repository’s front page. It acts as a project overview instead of just being another notes file.

Q11.  
gh auth login stored a secure token so Git can talk to GitHub without asking for a password each time. That’s why future pushes don’t need a password.

Q12.  
The front page shows the README.md file. GitHub does this automatically because README is meant to introduce the project.

Q13.  
Pushing did not change my local history. The commits stayed the same; they were just copied to GitHub.

Q14.  
A private repository exists on GitHub but only invited people can see it. If it doesn’t exist at all, nobody can access it because there’s nothing to find.