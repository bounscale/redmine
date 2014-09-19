{
  "name": "Redmine on Heroku with Bounscale",
  "description": "Redmine on Heroku with Bounscale",
  "keywords": [
    "redmine",
    "ruby",
    "bounscale"
  ],
  "website": "https://devcenter.heroku.com/articles/bounscale",
  "repository": "https://github.com/bounscale/redmine.git",
  "logo": "https://s3.amazonaws.com/assets.heroku.com/addons.heroku.com/icons/1208/original.png",
  "success_url": "/",
  "scripts": {
    "postdeploy": "bundle exec rake db:migrate"
  },
  "env": {
    "RAILS_SECRET__TOKEN": {
      "description": "A secret key for verifying the integrity of signed cookies.",
      "generator": "secret"
    },
    "WEB_CONCURRENCY": {
      "description": "The number of processes to run.",
      "value": "3"
    }
  },
  "addons": [
    "bounscale"
  ]
}
