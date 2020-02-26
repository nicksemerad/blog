# README

MVC -- building blocks of all apps
  Models
    - represents a database 
    - table base rules
  Views
    - what the user sees and interacts with
    - client side, front end
  Controllers
    - specify what we do when we hit a certain route
      - actions for these routes
    routes
      - traffic directors

Rails convention over configuration 
  - uses the same patterns, on different instances 


WHEN NAMING
models - singular
controllers - plural


Blog

Pages
  title: string
  author: string
  body: text
 #nicksemerad$ bundle exec rails g model Page title:string author:string body:text
 makes a new model with those keys

Comments

Migration
  -instructions to apply to database



  $ bundle exec rails g controller Pages index show new edit -- new controller with 4 pages


  CONTROLLER ACTIONS
    -index --show all pages
    -show --shows single page
    -new --new form
    -create --new object
    -edit --edit form
    -update --update object
    -destroy --deletes the object

ERB
  -embedded ruby
can run ruby code in html, must specify

<% rubycodegoeshere %>    this is a non-echoing tag, for a ruby object not displayed

<%= rubycodehere %>     this is an echoing tag, is displayed on screen