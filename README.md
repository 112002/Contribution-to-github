# Contribution-to-github
Steps to contribute in anyone's repository

- Go to the repository on github. (Say it’s by myfriend, and is called the_repo, then you’ll find it at https://github.com/myfriend/the_repo.) <br />
- Click the `Fork` button at the top right.
- You’ll now have your own copy of that repository in your github account.
- Open a terminal/shell.(I personally prefer Gitbash).
- Type
````
$ git clone git@github.com:username/the_repo
`````
       <br /> where username is your username.
- You’ll now have a local copy of your version of that repository.
- Change into that project directory (the_repo):
````
$ cd the_repo 
````
- Add a connection to the original owner’s repository.
```
$ git remote add myfriend git://github.com/myfriend/the_repo
```
- Note the distinction between git@github.com: in the first case and git://github.com/ in the second case. I’m not sure why these need to be the way they are, but that’s what works for me.
- Also note the first myfriend does not need to be the same as the username of myfriend. You could very well choose:
```
$ git remote add repo_nickname git://github.com/myfriend/the_repo
```
- 
