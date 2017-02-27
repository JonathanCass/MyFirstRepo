Git:

mkdir MyProject (whatevever you want)
cd MyProject
get init 
touch readme.md
[put stuff in readme file]
git add . 
git commit -m "initial commit"

Create Repo on github and grab the ssh link
	-looks like git@github.com:JonathanCass/MyProject.git
Add our Remote
	git remote add origin git@github.com:JonathanCass/MyProject.git
git push origin master

git add .
git commit -m "my message"
git push origin master