rails _3.2.13_ new demo_app
cd demo_app
vi Gemfile
bundle install
git init
git add .
git commit -m "Initial commit"
git remote add origin git@github.com:TedEwanchyna/demo_app.git
git push origin master
rails generate scaffold User name:string email:string
rake db:migrate
rails s
rails generate scaffold Micropost content:string user_id:integer
rake db:migrate
vi app/models/micropost.rb
vi app/models/user.rb
vi app/models/micropost.rb
git add .
git commit -a -m "Done with the demo app"
git push
vi Gemfile
rails s
ls db
sqlite3 db/development.sqlite3 
gem install taps
vi ../first_app/Gemfile
vi Gemfile
vi ../first_app/Gemfile
vi Gemfile
bundle install --without production
heroku create
git push heroku master
vi Gemfile
git commit -a -m "postgres for heroku"
git push heroku master
heroku logs
heroku logs
heroku rake db:migrate
heroku rename ted-demo-app
git push
