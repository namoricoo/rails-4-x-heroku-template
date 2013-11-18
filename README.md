# Rails 4.x, heroku, and HTML5 template

I was looking for a working rails 4.x optimized heroku template. I was unable to find one
that would allow me to create a demo rails app in under 2 minutes. So, I decided to share this
with the community to save other people time.


### Usage for Mac

`rails new projectname -m https://raw.github.com/namoricoo/rails-4-x-heroku-template'

	*Wait for the app to be created
	*Launch postgres93 app
	*Now run the following commands in the terminal
		$ bundle update
		$ psql 
		$ CREATE DATABASE rails_heroku_db_development;
		$ CREATE TABLE demo (field VARCHAR(255));
		$ \q
	
	* update initialize github with the following commands in terminal	
		$ git init
		$ git add .
		$ git commit -m "initial commit"
		$ git status
		# On branch master nothing to commit, working directory clean
		
	* now if your heroku account is already setup, run the following commands	
		$ heroku create --stack cedar
		$ git push heroku master
		
	* In your heroku file you can rename it to whatever you want.
	* Here is a link to the final product
	[]	 

### Minimum Requirements
* Postgres93 ( http://postgresapp.com/)
* Heroku Toolbelt (https://toolbelt.heroku.com/standalone)
* Local Postgres installation (http://postgresapp.com)
For more information you can go to the official heroku documentation
[https://devcenter.heroku.com/articles/getting-started-with-rails4]

