# Lost with git? Don´t worry you are not alone

<a href="#track_and_upload">1. Track current folder with git and upload it to GitHub</a></dt>

<img src="https://miro.medium.com/v2/resize:fit:600/0*VcMPr1unIjAIHw2j.jpg" width="400" height="300">


### Basic git workflow

<img src="https://static.packt-cdn.com/products/9781782168454/graphics/8454OS_01_4.jpg" width="600" height="400">



<a name="track_and_upload"></a>
## Initizalize repo from existing folder

Initialize git in your computer´s folder:
~~~
git init
~~~
Set remote origin in GitHub:
~~~
git remote add origin <github url of created repo>
~~~
Modify master branch to main:
~~~
git branch -m master main
~~~

### Basic Git Commands

Check status of files:
~~~
git status
~~~

Add all files to staging area prior to commit:
~~~
git add .
~~~

Add commit :
~~~
git commit -m "First Commit"
~~~

Add file to staging area and commit :
~~~
git commit -am "Two in one command"
~~~

Push changes to Github
~~~
git push
~~~

Pull any changes done remotely and update them into your local directory:

~~~
git pull
~~~

#### Branches

Creates and moves to branch:

~~~
git checkout -b "Name_of_new_branch"
~~~

Move to existing branch:

~~~
git checkout "name_of_existing_branch"
~~~

See existing branches:
~~~
git branch
~~~
