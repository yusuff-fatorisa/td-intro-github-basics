Git is a version control system.
It's used by individuals and teams while working on web development projects.
It's very good for collaboration and maintenance of codes or projects both individually and amongst team members
It helps make meaning of the progress and development of a particular project with the history of it and make it easier to switch back to a particular stage and version of the project.



Version Control is the process of keeping track of the various stages of the development of a project.
It's used to manage the progress of a particular project
It allows many developers on a team to work on a particular state of a project at a particular point in time.





After a project exists on a local machine, the following process helps to commit the project to a github repository
	* Create a github repo in the same name as that on your local machine
	* On your local machine, run the following commamnd on your terminal or text editor
          1. git init to initialize git in the local repository
          2. git status to confirm the actual status of the repository and see the changes in there
          3. git add . to add all the files to the staging area. all files to be committed must be first staged
          4. git status to view that the added files have been changed
          5. git commit -m "your_commit_message" to commit the changes and keep your track up to date
          6. git remote add origin "your_github_repository_unique_link" to link your local repo to your github repo
          7. git push -u origin master to push the localrepository to your github repository
