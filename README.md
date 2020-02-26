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

Comments

Migration
  -instructions to apply to database