# Rails API boilerplate

[![Build Status](https://travis-ci.com/ebkn/rails-api-boilerplate.svg?branch=master)](https://travis-ci.com/ebkn/rails-api-boilerplate)

Boilerplate for Rails api.

## Dependencies
- ruby 2.5.1p57 (2018-03-29 revision 63029) [x86_64-darwin17]
- Rails 5.2.1
- MySQL 5.7

### Usage
```sh
$ git clone git@github.com:ebkn/rails-api-boilerplate
$ cd rails-api-boilerplate
$ bundle install --path vendor/bundle
$ cp config/database.sample.yml config/database.yml
$ bundle exec rails db:setup
$ bundle exec rails s
```
