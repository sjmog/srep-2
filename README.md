# SREP

Spaced Repetition as a Service (SRaaS :stuck_out_tongue:)

- Rails
- PostgreSQL
- React
- Devise (for users)

Client-side routing is mostly handled by React-Router (except login/logout). Rails is optimised for API stuff.
Actual SREP handling happens directly through Rails.

### Getting Started

- `bundle install`
- `yarn install`
- `bin/rails db:create`
- `bin/rails db:migrate`
- `bin/rails db:seed` (also creates a user, `user@example.com` with password `password`)
- `bin/rails s`

(Optional: run `./bin/webpack-dev-server` to speed up JavaScript recompilation)
