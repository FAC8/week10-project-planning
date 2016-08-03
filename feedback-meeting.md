# Features

## Core
* See listings
  * Search by keyword in title or description
  * Filter by category
* Post listings
  * Categories. One category per item
  * Photo
  * Description
  * Title
  * Location - postcode
* Personal dashboard which which allows you to post/ delete old posts
  * Time out for post creation
* Facebook login - use name, photograph
* Ask users for their real emails and location on creation of account
* Image uploader

## Stretch
* Share listings on facebook
* Email updates
* Post listings
  * Condition
  * Size
  * Age
* Save favourite items

## Actions
* Choose image uploader
* Look into googlemaps API with react (iframe)

# Design
## Listings
* Grid view as standard
* List view can toggled to
* Map view can be toggled to
  * Stretch - When you toggle, transition cooly between views

## Dashboard
* Can look like either the grid or the list view

## Listing Page

## New Listing
* Looks like the listing page

## Actions
* Set up style-guide
* Finish off wireframes with new knowledge of features

# Tech Stack
## Database
Postgres more suited to what we're doing.

## Oauth
* Facebook login
* Going to implement cookies to save users between sessions

## Front-end
* SASS
* React
* No in-line styling

## Server
* Hapi
* Joi for email address validation

## Actions
* Learn how to write the script which builds the tables
* Write database schema
* Set up example.com with facebook api

# Code reviewers
![stalin](http://www.historytoday.com/sites/default/files/stalin.jpg)

* Research linters and config files and find one that will be appropriate. Sam
* Research tape to see if it will work in the way we want. Matt G
* Research setting up Travis with all the webhooks we want - Come up with a decision on code coverage to that will be enforced. Sam + Matt S
* Research how to do limited merge access in a repo. Mattia
* Writing the docs - include guidelines for reviewers. Everyone
* Deliverable by close of play - A repo with fully configured package.json, travis, webhooks, basic tests. Everyone
