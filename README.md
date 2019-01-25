# rails-templates
templates for rails applications mostly inspired by [lewagon/rails-templates](https://github.com/lewagon/rails-templates)

## Devise
Get a minimal rails 5.1+ app ready to be deployed on Heroku with Bootstrap, Simple form and debugging gems plus a Devise install with a generated User model.
Diff from original template by lewagon : 
- yarn add Bootstrap@4.2.1
- gem 'slim-rails'
- gem 'devise-i18n'

```
rails new \
  --database postgresql \
  --webpack \
  -m https://raw.githubusercontent.com/Pagehey/rails-templates/master/main.rb \
  APP_NAME
  ```
