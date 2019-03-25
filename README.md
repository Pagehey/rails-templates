# rails-templates
templates for rails applications mostly inspired by [lewagon/rails-templates](https://github.com/lewagon/rails-templates)

## Devise
Get a minimal rails 5.1+ app ready to be deployed on **Heroku** with **Bootstrap 4**, Simple form and debugging gems plus a Devise install with a generated User model.
Differences from original template by lewagon :
- yarn add Bootstrap@4.2.1
- gem 'slim-rails'
- gem 'devise-i18n'
- default_locale = :fr

```
rails new \
  --database postgresql \
  --webpack \
  -m https://raw.githubusercontent.com/Pagehey/rails-templates/master/devise.rb \
  APP_NAME
  ```
**With Clever Cloud conf files**

```
rails new \
  --database postgresql \
  --webpack \
  -m https://raw.githubusercontent.com/Pagehey/rails-templates/master/clever_cloud/master/devise.rb \
  APP_NAME
  ```
