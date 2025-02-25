# AgendaMeYa API

This is the API backend for the AgendaMeYa application, built with Ruby on Rails.

## Prerequisites

- Ruby 3.2.2
- Rails 7.0.8
- PostgreSQL

## Setup

1. Clone the repository
2. Install dependencies:
   ```bash
   bundle install
   ```
3. Setup database:
   ```bash
   rails db:create db:migrate
   ```
4. Start the server:
   ```bash
   rails server
   ```

## Testing

Run the test suite with:
```bash
rspec
```