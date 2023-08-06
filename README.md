This shell script decreases your working-time by exchanging the sequence of pushing new edits into github with one command instead of doing :
git add .
git commit -m "$your-commit-message"
git push

note:
this script works without problems in case you want to push at the same branch that was edited.
the script will add all new modifications.

