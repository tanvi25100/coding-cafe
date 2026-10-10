##1 
--global means that this setting applies to every git repositry. Without --global, it would only apply to my current repositry.

##2
A hidden folder .git appeared. Using ls does not show it because it starts with a dot and is a hidden file. It is Git's database for this project and stores all commits, branches, and settings.

##3
git status said "No commits yet" and listed around 5-7 untracked entries: my lab folders (lab1/, lab2/, lab3/), README.md, and some things I did not write
 .venv/ (thousands of files of installed packages),__pycache__/ (Python's compiled files) 

##4
The entries that i did not write disappeared and a new file gitignore appeared instead.

##5 
It should be commited. It is part of the project's setup, so committing it saves the ignore rules in the history, and anyone who gets a copy of the repositry  uses the same rules.


##6
It moved from "Untracked files" to "Changes to be committed". In the three-places model, git add moved it from the working directory into the staging area, so it is ready to go into the next commit.


##7
Git printed a line with the branch, the short commit ID and my message, followed by a summary saying how many files changed and how many lines were inserted. It showed that 5 files were changed.

##8
They are the commit hash. Every commit has a unique ID which can be used to refer to that exact commit.

##9 
1. Edit a file
2. Stage it (git add)
3. Commit it (git commit -m "message")
4. Check the result (git status)

##10
README.md is a standard name that GitHub recognises. A  README in the top folder is displayed automatically on the repository's front page. It is the first thing a visitor reads, so it explains 
what the project is how it is organised.

##11
gh auth login signed me in through the browser and saved a login token on my laptop. It also set Git up to use that token automatically, so when I push, Git proves who I am without asking for a password.

## Q12
The README.md is shown as formatted text below the list of files. GitHub automatically displays the README from the top folder because it is the standard file that introduces a project to visitors.

## Q13
No. git log --oneline shows the same commits with the same hashes as before. Pushing only copied my history to GitHub, the only difference is that the log now also shows origin/main, so 
GitHub's copy is at the same commit as mine.

## Q14
A private repository exists on GitHub, it is stored and backed up online, but only I and the people I invite (like the TAs) can see it.
A repository that does not exist on GitHub only lives on my laptop, so nobody else can see it.



