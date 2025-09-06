# README

# Generate a controller/view

```
rails g controller home index
```

# Check routes

```
rails routes
```

# Create a scaffold

```
rails g scaffold friends first_name:string last_name:string email:string phone:string twitter:string
```

Supported Types: https://guides.rubyonrails.org/v3.2/migrations.html#supported-types

# Push migration into the DB

```
rails db:migrate
```

# Install a package (devise)

1. Add to gemfile from https://rubygems.org/gems/devise

2. Install all gem in the gemfile:

```
bundle install
```

# Run the 'devise' generator

```
rails generate devise:install
```

Then, follow the instructions.

# Create a model (will be configured with the default Devise modules)

```
rails generate devise user
```

This creates a migration.

# Push migration

```
rails db:migrate
```

Devise Documentation: https://github.com/heartcombo/devise
