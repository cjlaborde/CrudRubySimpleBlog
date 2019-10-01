# See Routes
rake routes

# Create controller
rails g controller Pages

# Create model to save to databse
rails g model Post title:string body:text

# migrate database
rake db:migrate

# Style Ruby
https://rubyplus.com/articles/3991-Twitter-Bootstrap-4-Forms-and-Navigation-in-Rails-5


# create model with references
▶ rails g model Comment username:string body:text post:references

