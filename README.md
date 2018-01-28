# README

## CLIENT CHANGES

#### COM+SHIFT+F client_name

* client_name.jsx including internals

* application.html.erb head-data

* config/application.rb modulename

* config/database.yml
  * database: development
  * #username:
  * #database: test
  * database: production
  * username:
  * password: <%= ENV['CLIENT_NAME_DATABASE_PASSWORD'] %>

* config/environments/production.rb
  * config.active_job.queue_name_prefix = "client_name#{Rails.env}"

* package_json "nam": "client_name"

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
