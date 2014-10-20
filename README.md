# Stripe Stream

`stripe-stream` is a Rails app that exposes near real-time streaming Stripe account data in a dashboard format. It’s meant to demonstrate how web sockets can be used to improve the system dashboard experience.

## Installation

- `bundle install`
- `rake db:setup`
- `rails server`

## Key ideas

- Keep a record of changes to Stripe account state by listening to Stripe webhooks.
- Stream changes to subscribed front-end clients
- Display information in a readable format on the front-end with animation.
