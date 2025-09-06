# README

# generate a controller (-> view)

rails g controller home index

# create a scaffold

rails g scaffold friends first_name:string last_name:string email:string phone:string twitter:string

Supported Types:
https://guides.rubyonrails.org/v3.2/migrations.html#supported-types

# push that migration into the DB

rails db:migrate
