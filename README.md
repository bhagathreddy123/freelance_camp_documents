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


FreelanceDocument.create!(title: "A Totally Different One",description: "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation",file_url: "https://docs.google.com/document/d/1UUgAob6ZpivgkgCbMD84JMMRc1flrzCPKybtQoAfASo/edit?usp=sharing",image_url: 'https://s3.amazonaws.com/devcamp-static/images/freelance-img-2.jpg'
 	)
