### Basic git workflow

<img src="https://static.packt-cdn.com/products/9781782168454/graphics/8454OS_01_4.jpg" width="600" height="400">

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