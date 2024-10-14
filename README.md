# Odin Kittens

This project is part of The Odin Project: [Kittens API](https://www.theodinproject.com/lessons/ruby-on-rails-kittens-api) in the Ruby on Rails curriculum.

## Learning Objectives

By the end of this project, you will be able to:

- Create a Rails application that serves both HTML and JSON responses.
- Implement RESTful routes and controller actions for a resource.
- Use Active Record to manage data through models.
- Handle flash messages for user notifications.
- Test API responses using the `rest-client` gem.

## Assignment Overview

**HTML Setup:**

1. **Create Rails App**: Generate a new Rails application (`odin-kittens`) and initialize a Git repository.
2. **Generate Kitten Model**: Create a `Kitten` model with attributes: `name`, `age`, `cuteness`, and `softness`.
3. **KittensController**: Implement a `KittensController` with routes for all 7 RESTful actions.
4. **Root Route**: Set `kittens#index` as the root route and build HTML views for all actions.
5. **Flash Messages**: Add flash messages for success/error handling and delete links for kittens.
6. **Testing**: Ensure all controller actions are functioning correctly.

**JSON API Setup:**

1. **REST Client Requests**: Use the `rest-client` gem to make requests to the app.
2. **JSON Responses**: Modify `KittensController#index` to respond with JSON and implement a JSON response for the `show` action.
3. **Test API Responses**: Validate API responses using the `RestClient`.

## Features

- **RESTful API**: Provides both HTML views and JSON API endpoints for accessing kittens data.
- **CRUD Operations**: Implement full CRUD functionality for kittens through a web interface.
- **Flash Notifications**: User-friendly messages to indicate success or failure of actions.

## Technologies Used

- Ruby on Rails
- ActiveRecord for database management
- `rest-client` gem for API requests

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/jambalong/odin-kittens.git
   ```

2. Navigate to the project directory:
   ```bash
   cd odin-kittens
   ```

3. Install dependencies:
   ```bash
   bundle install
   ```

4. Set up the database:
   ```bash
   rails db:create
   rails db:migrate
   ```

5. Start the Rails server:
   ```bash
   rails server
   ```

Access the application at `http://localhost:3000`.
