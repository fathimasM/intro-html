git fetch origin
git checkout -b add-style origin/add-style
git merge main

git checkout main
git merge --no-ff fathimasM-patch-1
git push origin main

git checkout main



