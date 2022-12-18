or create a new repository on the command line

echo "# RS-JavaScript-Front-end" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:leoxalangoz/RS-JavaScript-Front-end.git
git push -u origin main

or push an existing repository from the command line

git remote add origin git@github.com:leoxalangoz/RS-JavaScript-Front-end.git
git branch -M main
git push -u origin main


!!! use 'master' insteed 'main'

git branch - check how many branch has my repository
git checkout ...name-branch - switching between branch
git checkout -b ...name-new-branch... - add new 