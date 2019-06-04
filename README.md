## Objectives
* Deploy node.js + knex + psql apps to Heroku

## Getting started
```
heroku create # create heroku project from the command line
heroku addons:create heroku-postgresql:hobby-dev

npm i -g knex

heroku config:set DATABASE_URL={your_database_url}
heroku config:set NODE_ENV=production

heroku run knex migrate:latest
heroku run knex seed:run

# POSTMAN environment

```

## Resources
https://devcenter.heroku.com/articles/config-vars#accessing-config-var-values-from-code