###install git
> sudo apt-get install git -y

####Set Up Git:
> git config --global user.name "Vamshi-dhar"
> git config --global user.email "vamshi.analyst2013@gmail.com"

###other commands
> git init #turns directory to gt repository.
> git status  #Current state of repository.
> git clone (url) # to clone repository from any public account.

> git add (file names) # to add the file to staging area for git.only files in staging area are considered for commit.

> git add . #to add all files in given repository


> git commit -m "(committed message)"
> git push -u origin master
> git remote add origin master (url)