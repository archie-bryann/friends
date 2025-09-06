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
