---
layout: page
title: rails
permalink: /rails/
---

# Rails

## RoRR (Ruby On Russian Rails)

- https://github.com/svenfuchs/rails-i18n/ dates, ActiveRecord errors

- https://github.com/fesplugas/rails-translate model attributes

- https://github.com/glebm/i18n-tasks analysis

- https://github.com/balinterdi/i15r replace plain strings to t('path.string')

## perfomance in development

`config.assets.debug = true` in development config, if app's views render too long

http://stackoverflow.com/questions/15317048/diagnosing-the-cause-of-slow-view-rendering

## sidekiq daemonization

https://github.com/mperham/sidekiq/wiki/Deployment#daemonization

## rake

`RAILS_ENV=production bin/rake assets:precompile`

## problems

- [ ] How to debug sass precompilation errors?
