# Lost with git? Don´t worry you are not alone

<a href="#track_and_upload">1. Initizalize repo from existing folder</a>

<a href="#basic_commands">2. Basic commands</a>

<a href="#branches">3. Branches</a>









<a name="track_and_upload"></a>
## 1. Initizalize repo from existing folder

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





<a name="basic_commands"></a>
### Basic Git Commands

<img src="https://static.packt-cdn.com/products/9781782168454/graphics/8454OS_01_4.jpg" width="600" height="400">

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

<a name="branches"></a>
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


<img src="https://miro.medium.com/v2/resize:fit:600/0*VcMPr1unIjAIHw2j.jpg" width="400" height="300">
