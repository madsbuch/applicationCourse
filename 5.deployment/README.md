Deployment
==========

Objective
---------
Following is the objectives of the first workshop:
* Knowledge on deployment techniques

Terminology
-----------
* Static page

Schedule
--------
1. Introduction to Static pages
2. Setting a Wintersmith blog up in Notrous
3. Introduction to github pages
4. Deplying the blog on github


Setup wintersmith
-----------------

1. Login to your nitrous.io box
2. Install wintersmith: `~$ npm install -g wintersmith`
3. Change directory to your workspace: `~$ cd workspace`
4. Create you blog: `wintersmith new blog-name`
5. go into the project-folder: `cd blog-name`
6. Start preview: `wintersmith preview`
7. In nitrous, press the preview button, and click _preview 8080_


Deploying blog to Github
------------------------

1. Create an account on github
2. Create a new repository with the name "your username".github.io
3. add git to your blog:
   a. In nitrous, cd intro the project folder
   b. Initialise git: `git init`
   c. Add files: `git add -A :/`
   d. Commit: `git commit -a -m "initial commit"`
   e. Add the new repository as remote: `git remote add url-to-repo`
4. Build the project:
   a. Add following to config.json: `,"output": "."`
   b. Build the project: `wintersmith build`
5. Push the project to github: `git push origin master`
