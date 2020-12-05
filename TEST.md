rm -rf .git
git init
git add .
git commit -m "Project Reset"
git remote add origin https://github.com/eltoroit/test-20201205a.git
git push origin master

##

git remote add heroku https://git.heroku.com/test-20201205a.git
git push heroku master
