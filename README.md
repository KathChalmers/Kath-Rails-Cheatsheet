# Kath-Rails-Cheatsheet
My favorite tutorials, gems and frequently used commands for easy reference


# My Favorite Rails Tutorials

See gem tutorials below in Favorite Gems list

How to Build a CSV Uploader into a Ruby on Rails Application
https://www.youtube.com/watch?v=W8pohTautj8

Import Data into Rails from a Spreadsheet
https://www.youtube.com/watch?v=v2Y7cja0b4c



# My Favorite Gems

Administrate
https://github.com/thoughtbot/administrate
Tutorial: https://gorails.com/episodes/administrate

Devise
https://github.com/plataformatec/devise
Tutorial: 




# Frequently Used Commands


Git
______________

git init
Start a new repository

git add .
git add file
 > Add all the files or a single file

git commit -m “commit message about feature or change”
 > Commit the added files to the repository and describes them

git status
 > Shows all the files that need to be committed

git branch
 > Shows all the branches in the repository with * next to the current one

git branch branch-name
 > Creates a new branch

git checkout master
git checkout name-of-branch
 > checks out a copy of the target branch onto your local directory
 
 git push origin 
  > sends local changes to remote repository


Rails 5
______________

rails g scaffold Company name:string address1:string address2:string city:string state:string zip:string phone:string url:string



Devise
______________

before_action :authenticate_user!
