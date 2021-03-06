# Computing Society app for Android

![](http://www.logospike.com/wp-content/uploads/2015/10/Android_Logo_09.png)

A companion project to the [Computing Society Website](https://github.com/UWICompSociety/uwi-cs-webapp/)

The Computing Society App for android is a companion project of the Computing Society website and will support/mirror many of the same features. In light of this, the aim of the app is also to give a convenient outside view of the work of the Society as well as the people responsible.

## Contributions

To contribute to this project, you will need to do the following:

#### Fork the repository to your GitHub account by clicking the relevant button above
#### Clone your forked repository to your development computer. This is the repository that you will do your work in
```
git clone https://github.com/<username>/uwicompsociety-android
```

#### Add this repository as an upstream remote branch. 
  * This will allow you to pull any changes that have been made to the code since you forked it
```
git remote add upstream https://github.com/UWICompSociety/uwicompsociety-android
```

#### Do some work! 
  * This is the fun part where you actually write some code. Your purpose for forking this repository in the first place.
  * It is key that you put each logical component that you want to contribute on its own branch. For example, let's say you have already forked the repository and cloned it to your computer. When you are ready to do some work, doing these commands as a rule will always help:
  
  ```
  $ git checkout master
  $ git pull upstream master && git push origin master
  $ git checkout -b <branch_name>
  ```
  
  * These commands, in order, ensures that you're working on the master branch, syncs your local repo with the origin (to perhaps pull some changes since you forked) and then updates your remote repo with changes, if any, and creates the and moves you to the branch you want to develop your new feature on.
  
#### Create a pull request. 

* To create a PR you need to push your branch to the origin remote and then press some buttons on GitHub.

Once you have committed your changes, push the new branch with

```
$ git push -u origin <branch_name>
```

* This will create the branch on your GitHub project. The -u flag links this branch with the remote one, so that in the future, you can simply type git push origin or just git push.

* Swap back to the browser and navigate to your fork of the project and you'll see that your new branch is listed at the top with a handy "Compare &amp; pull request" button:

## Contributors
  * [@sultanofcardio](https://github.com/sultanofcardio)
