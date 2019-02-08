# Kath-Rails-Cheatsheet
My favorite tutorials, gems and frequently used commands for easy reference


## My Favorite Rails Tutorials

See gem tutorials below in Favorite Gems list  

How to Build a CSV Uploader into a Ruby on Rails Application  
https://www.youtube.com/watch?v=W8pohTautj8

Import Data into Rails from a Spreadsheet  
https://www.youtube.com/watch?v=v2Y7cja0b4c

Intro to Rake  
https://www.youtube.com/watch?v=gR0YfJrg9pg

Rails Tour  
https://rubyonrails.org


## My Favorite Gems

Devise  
https://github.com/plataformatec/devise  
Tutorial: 


Rails Layout  
rails generate layout:install bootstrap4




## Frequently Used Commands

______________
RVM
______________

rvm install 2.5.3

rvm use 2.5.3

which ruby

ruby -v

rvm gemset create gemsetname

rvm use 2.5.3@gemsetname --create

rvm gemset use gemsetname

______________
Git
______________

git init  
Start a new repository

git add .  
git add file  
Add all the files or a single file

git commit -m “commit message about feature or change”  
Commit the added files to the repository and describes them

git status  
Shows all the files that need to be committed

git branch  
Shows all the branches in the repository with * next to the current one

git branch branch-name  
Creates a new branch

git checkout master  
git checkout name-of-branch  
Checks out a copy of the target branch onto your local directory
 
git push origin  
sends local changes to remote repository

______________
Rails 5
______________

Rails Command Line Guide: https://guides.rubyonrails.org/command_line.html  

add -h at the end of a command for help using it  

rails s  
rails server  

rails c  
rails console

rails db  

rails new appname  
rails new appname --database=postgresql  
(creates the app in a directory named appname - cd to enter app)  

rails g scaffold Company name:string address1:string address2:string city:string state:string zip:string phone:string url:string  

rails generate controller ControllerName action1 action2
rails generate model  

rails destroy  
(Can be used to remove stuff created by rails generate.)  

bin/rails assets:clobber  
Clear the public/assets folder  

______________
Rake
______________
rake routes  


______________
Devise
______________

before_action :authenticate_user!  
before_filter :is_admin?
  
  
