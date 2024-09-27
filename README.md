# README

# User Authentication System

This project is a simples blog alike app. The purpose of this app was to demonstrate skills on how to use turbo-links in Ruby on Rails.

## Features

- Session tracking ...but didn't spent time developping an user autthetication with login and password (already made two other pojects with this feature)
- CRUD functions for blog posts (with Action text) 
- CRD functions for comments (with Action Text)
- Turbo-updates in most actions

## Requirements

- Ruby 3.3.4
- Rails 7.2.1
- Database: SQLite3
- Package manager for Java Script: Yarn

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/Chicoz0/blog_with_turbo
   cd blog_with_turbo

2. Install dependencies:

   ```sh
   bundle install

3. Install JavaScript dependencies:

   ```sh
   yarn install   

4. Set up the database:

   ```sh
   rails db:create
   rails db:migrate

5. Start the server:

   ```sh
   rails server

6. Access the application at http://localhost:3000.

## Dependencies

### Ruby Gems
- `rails (~> 7.2.1)`
- `sqlite3 (>= 1.4)`
- `puma (>= 5.0)`
- `turbo-rails`
- `stimulus-rails`
- `jbuilder`

## Contribution

1. Fork the project.
2. Create a new branch (git checkout -b feature/new-feature).
3. Commit your changes (git commit -am 'Add new feature').
4. Push to the branch (git push origin feature/new-feature).
5. Create a new Pull Request.
