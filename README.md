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
# task_manager

# Define CRUD.
- Create
- Read 
- Update
- Delete


# Define MVC:

- Models
- Views (Serializers)
- Controllers

# What two files would you need to create/modify for a Rails application to respond to a GET request to /api/v1/tasks, assuming you have a Task model.
1. `config > routes.rb`
2. `app > v1 > tasks_controller.rb`

# What are params? Where do they come from?
- params are the parameters we setup in our routes so that when they're included in the URL request they can be passed to the database to access specific inforation within a table.
they can come from a url, orform data

# What is the purpose of a serializer?
- To adjust the data about the object that is returned to the front end in json.  Instead of returning all the params you can specifcy which data should be displayed to the front end when the object is requested.
