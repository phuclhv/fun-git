# Fun-Git
Tricks in git using only command line that I found interesting. Some commands are for Windows user only, but you can easily find equivalent in Linux.

### Create a repo
I tried to create repo "fun-git" for username "phuclhv". 
~~~
mkdir fun-git
cd fun-git
git init
curl -u phuclhv https://api.github.com/user/repos -d "{\"name\":\"fun-git\"}"
type nul > README.md
git add README.me
git commit -m "Initial commit"
git remote add origin git@github.com:phuclhv/fun-git.git
git push origin master
~~~
References: 

https://stackoverflow.com/questions/2423777/is-it-possible-to-create-a-remote-repo-on-github-from-the-cli-without-opening-br

https://gist.github.com/robwierzbowski/5430952

### Delete a git folder
I tried to delete "fun-git" folder 
#### Command Promt
~~~
del /s /q fun-git
~~~

