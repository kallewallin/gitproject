readme.txt

// Bas status
git status

// Diff på unstaged filer
git diff 

// Diff på alla filer
git diff --cached

// Diff på staged filer
git diff --staged

// Basic commit
git commit -m "Commit message"

// Commit with editor
git commit

// Commit with editor and diff included
git commit -v

// Commit without needing to add files
git commit -a -m "Commit message"

// "Add" en fil till staged (Skall göras på båda tillagda och ändrade filer)
git add [filnamn]

// "Add" en borttagen fil till staged
git rm [filnamn]