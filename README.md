Navigate to my folder
git init -> creates the repository
Created file index.html in folder
git add index.html -> add file to staging area
git commit -m "My first commit" -> create commit with message
git push origin -> push changes to github
Added some content to html file. Created file style.css in folder
git add --all -> add all files in folder to staging area
git commit -m "change html, add css" -> create commit with message
git push origin -> push changes to github
Created file readme.txt in folder
git add readme.txt -> adding only this file to staging area
git commit -m "adding readme file" -> create commit with message
git push origin -> push changes to github
Updating content of html file
git add index.html -> adding html file to staging area
git commit -m "adding headings to html" -> create commit with message
git push origin -> push changes to github
echo PASSWORD=12345 > .env -> create .env file in folder
git status -> confirm .env file is untracked
echo .env > .gitignore -> add file to .gitignore
git status -> confirm .gitignore is not only untracked file
git add .gitignore -> add .gitignore to staging area
git commit -m "Add .gitignore" -> create commit with message
git add .env -> confirm .env is ignored
git push origin -> push changes to github

