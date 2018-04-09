# README

Heroku production URL:

https://salty-crag-87321.herokuapp.com/

## Developing locally

[Docker](https://docs.docker.com/compose/install/#prerequisites) is used for developing locally

```bash
# Leave this running in a terminal window
docker-compose up

# bundle gems
bundle install

# set up database
bundle exec rails db:migrate

# import seed data from Goodreads
rake import:goodreads

# start the server
bundle exec rails s
```
