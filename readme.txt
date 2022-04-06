echo "# JenkinsDemo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/benbay/JenkinsDemo.git
git push -u origin main
