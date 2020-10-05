### abdulmukit98.github.io

	git config --global user.name "Your name"
	git config --global uuser.email "Your emaill"
	
	git clone https://github.com/abdulmukit98/abdulmukit98.github.io.git
	git status
	git add --all
	git commit -m "new commit"
	git push -u origin master

### pull

	pull overwrite local file and match to remote repo
	creat a file in remote repo
	pull it to local repo

	in abdulmukit98.github.io folder
	git pull https://github.com/abdulmukit98/abdulmukit98.github.io.git
	or sumply git pull

### force pull
	
	in abdulmukit98.github.io path
	git fetch --all
	git reset --hard origin/master
