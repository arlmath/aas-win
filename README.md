# README

1. Install Ruby

2. Install rails via gem

    gem install rails

3. Check if rails is install or not

    rails --version

4. Install postgres (remember username & password will add them in database.yml file in future)

5. Create rails app

    mkdri aas
    cd aas
    rails new aas -d=postgresql 
    (You need to create database for your environment)
    rails db:create (database will be created)

    Make sure your postgres username and password is added into database.yml file 

    rails db:migrate
    rails server

    # Yay! You’re on Rails!