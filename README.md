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
 rails new freelance_camp_documents --api -T -d postgresql
 rails db:create
rails g scaffold FreelanceDocument title:string description:string file_url:text image_url:text