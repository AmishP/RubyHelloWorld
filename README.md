# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


To create a new model use the following command:
rails generate model User firstName:string lastName:string 

This creates a new table with 2 columns of string type

rake db:migrate this applies the new model

To create a controller/view with the page titled index, use the following command:
rails generate controller Users index 