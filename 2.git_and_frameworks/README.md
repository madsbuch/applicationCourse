Git and Frameworks
==================

<!-- toc -->
<!-- toc stop -->

This is the second workshop in the series. This is going to be more interactive
with more focus on your individual projects.

Objectives
----------

* Understand what a framework is
* Be able to use git
* Have an understanding of the given framework

Terminology
-----------
* crossplatform
* Framework
  * Fullstack framework
  * Clientside framework
  * Serverside framework
* Git
  * pull
  * push
  * commit
  * remotes
  
Schedule
--------
1. Idag: frameworks, git and the projects.
2. Common platform: nitrous.io
2. What is a framework.
3. Downloading and getting to know your framework (17:15)
4. Bootstrapping your project (18:00)
5. Adding Git to the project



Descriptions
------------

### The Meteor framework
Meteor is a fullstack framework. It is transparent with respect to server and
client. The forces of the framework is that it has a modular template system,
it is very easy to work with and it allows for very modern web applications.

This framework is suited for web-applications in a browser rather than mobile
applications.

### Phonegap
Phonegap is a tool that take HTML-websites and packages them for mobile phones.
This is an very easy way to make crossplatform mobile apps.

### JQuery Mobile
JQuery mobile is used for writing interfaces to applications to mobile phones.

Exercises
---------

### Create nitrus.io account
1. Go to [nitrous.io](https://www.nitrous.io/) and sign up for an account.
2. Log into the webinterface and write following (ctrl + shift + v to paste):
   * `git config --global user.name "Your Name"`
   * `git config --global user.email "you@example.com"` 

### Creating Repository on Bitbucket
1. Sign up for an account at [Bitbucket](https://bitbucket.org/)
2. create new repository.

### Setting up a Meteor project (with nitrus.io)
1. [Follow this guide](https://www.discovermeteor.com/blog/meteor-nitrous)


### Setting up a Phonegap project
1. log into nitrous.io and the web-editor
2. install phonegap by `npm install -g phonegap`
3. enter the workspache folder: `cd workspace`
4. create phonegap project: `phonegap create app-name`
5. follow [this guide](http://demos.jquerymobile.com/1.2.0/docs/about/getting-started.html)
   to start your project

### Pushing the project to git
1. Go into your project folder: `cd /workspace/app-name`
2. Initialize git: `git init`
3. Add the files to git: `git add -A :/`
4. Commit changes to git: `git commit -a -m "describe your changes"`
5. Add bitbucket as remote: `git remote add bitbucket url-from-bitbucket`
6. Push it! : `git push bitbucket master`

### Setting up build.phonegap.com
1. create a user at
