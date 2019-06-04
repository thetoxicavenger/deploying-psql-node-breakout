## Objectives
* Deploy node.js + knex + psql apps to Heroku

## Getting started
```
heroku create # create heroku project from the command line
heroku addons:create heroku-postgresql:hobby-dev
npm i -g knex
heroku config:set DATABASE_URL={your_database_url}
```

## Resources
https://devcenter.heroku.com/articles/config-vars#accessing-config-var-values-from-code