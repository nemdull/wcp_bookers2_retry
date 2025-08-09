# WebCamp Bookers 2 (Retry) Application

This is a Ruby on Rails booking application, possibly a revised version of a previous project. It includes RSpec for testing.

## Technologies

- Ruby on Rails
- Ruby
- JavaScript
- RSpec

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone git@github.com:nemdull/wcp_bookers2_retry.git
   cd wcp_bookers2_retry
   ```
2. Install Ruby dependencies:
   ```bash
   bundle install
   ```
3. Install JavaScript dependencies (if any, check `package.json`):
   ```bash
   yarn install # or npm install
   ```
4. Database setup:
   ```bash
   rails db:create
   rails db:migrate
   # rails db:seed (if seed data is available)
   ```
5. Run the application:
   ```bash
   rails s
   ```

## How to Run Tests

```bash
rspec
```