Insidevilla
================

This application was generated with the [rails_apps_composer](https://github.com/RailsApps/rails_apps_composer) gem
provided by the [RailsApps Project](http://railsapps.github.io/).

Rails Composer is open source and supported by subscribers. Please join RailsApps to support development of Rails Composer.

Problems? Issues?
-----------

Need help? Ask on Stack Overflow with the tag 'railsapps.'

Your application contains diagnostics in the README file. Please provide a copy of the README file when reporting any issues.

If the application doesn't work as expected, please [report an issue](https://github.com/RailsApps/rails_apps_composer/issues)
and include the diagnostics.

Ruby on Rails
-------------

This application requires:

- Ruby 2.3.1
- Rails 4.2.4

Learn more about [Installing Rails](http://railsapps.github.io/installing-rails.html).

Getting Started
---------------

### 1. Clone repo
```
$ git clone git@bitbucket.org:pav31/insidevilla.git
$ gem install bundler
$ bundle install
```
You may also need to install Node.js

### 2. Install and setup PostgreSQL.
Create postgres user with password.

3.
Edit `env.example` pasting postgres user and password and save it as `.env.local`
To generate `SECRET_KEY_BASE`, do the following.

```
$ rails c
$ Devise.friendly_token(128)
```


Documentation and Support
-------------------------

Deploying to production
-------------
```
$ cap production deploy
```

List all available tasks:
```
$ cap -T
```

Issues
-------------

Similar Projects
----------------

Contributing
------------

Credits
-------

License
-------
