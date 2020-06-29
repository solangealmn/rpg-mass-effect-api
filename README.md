# API RPG MASS EFFECT

* Ruby version '2.5.5'
* Rails version '6.0.3.1'

## To start the project:

Run `bundle install` on terminal.

After all gems are installed, run `rails db:create`. That will create de database on Postgres.

At this point, it's very likely you will run into a problem with postgres. you have to get it started locally before creating the database, here what solved the problem was  running `pg_ctl -D /usr/local/var/postgres -l /usr/local/var/postgres/server.log start` on terminal.

