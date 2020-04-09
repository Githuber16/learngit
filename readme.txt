Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
Git tracks changes.

echo "# justry" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:learn136/justry.git
git push -u origin master