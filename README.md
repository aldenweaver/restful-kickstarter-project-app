# README

Kickstarter
Welcome to Kickstarter. Assume we have a model called Project that inherits from ActiveRecord::Base, a corresponding table called projects, and a controller called ProjectsController that inherits from ApplicationController

For each of the following descriptions, write out the corresponding:

The HTTP Verb and URL (ie 'GET '/dogs'')
The rails controller action (ie 'dogs#index')
The corresponding CRUD action (ie 'READ)
The corresponding ActiveRecord method (ie 'all')

Actions
Displays all of the projects
Displays information about one project
Displays a form to create a new project
Creates a new project based on given parameters
Displays a form to update an existing project
Updates an existing project with given parameters
Deletes an existing project

**************************************************
ACTIONS:
Displays all of the projects
    The HTTP Verb and URL (ie 'GET '/dogs'')
        GET '/projects'
    The rails controller action (ie 'dogs#index')
        projects#index
    The corresponding CRUD action (ie 'READ)
        READ
    The corresponding ActiveRecord method (ie 'all')
        all
Displays information about one project
    The HTTP Verb and URL (ie 'GET '/dogs'')
        GET '/projects/id'
    The rails controller action (ie 'dogs#index')
        projects#show
    The corresponding CRUD action (ie 'READ)
        READ
    The corresponding ActiveRecord method (ie 'all')
        find_by_id
Displays a form to create a new project
    The HTTP Verb and URL (ie 'GET '/dogs'')
        GET '/projects/new'
    The rails controller action (ie 'dogs#index')
        projects#new
    The corresponding CRUD action (ie 'READ)
        CREATE
    The corresponding ActiveRecord method (ie 'all')
        create
Creates a new project based on given parameters
    The HTTP Verb and URL (ie 'GET '/dogs'')
        POST '/projects"
    The rails controller action (ie 'dogs#index')
        projects#show
    The corresponding CRUD action (ie 'READ)
        CREATE
    The corresponding ActiveRecord method (ie 'all')
        create
Displays a form to update an existing project
    The HTTP Verb and URL (ie 'GET '/dogs'')
        GET '/projects/id/edit'
    The rails controller action (ie 'dogs#index')
        projects#edit
    The corresponding CRUD action (ie 'READ)
        READ
    The corresponding ActiveRecord method (ie 'all')
        find_by_id
Updates an existing project with given parameters
    The HTTP Verb and URL (ie 'GET '/dogs'')
        PATCH '/projects/id'
    The rails controller action (ie 'dogs#index')
        projects#show   
    The corresponding CRUD action (ie 'READ)
        UPDATE
    The corresponding ActiveRecord method (ie 'all')
        find_by, then update
Deletes an existing project
    The HTTP Verb and URL (ie 'GET '/dogs'')
        DELETE '/projects/id'
    The rails controller action (ie 'dogs#index')
        projects#index
    The corresponding CRUD action (ie 'READ)
        DELETE
    The corresponding ActiveRecord method (ie 'all')
        find_by, then destroy

**************************************************
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
