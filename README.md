# README

## CLIENT CHANGES

#### COM+SHIFT+F client_name

Change the following naming information

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
