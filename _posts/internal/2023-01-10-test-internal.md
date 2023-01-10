---
title: "Migrate Postgres database from Heroku to localhost"
author: DTOSNER
date: 2022-04-22 19:00:00 -0000
categories: [internal]
tags: [postgres, heroku, internal]
---

Mluvil jsem s p. Vlastovkou

## Just commands
---
```console
cd rails/project/repo/path
sudo service postgresql restart
rails db:drop
rails db:drop DISABLE_DATABASE_ENVIRONMENT_CHECK=1
rails db:create
rails db:migrate
pg_restore --verbose --clean --no-acl --no-owner -h localhost -U user -d database_name '/location/of/downloaded/db/backup'
```
---