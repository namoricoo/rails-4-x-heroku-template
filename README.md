# Rails 4.x heroku ready template

1) Initial commitpsql
2) Use the following commands to create 'demo_name' user with 'demo_password' password


	<h3>On A Mac</h3>
	<ol>
		<li>open terminal</li>
		<li>psql</li>
		<li>CREATE USER demo_user WITH PASSWORD 'demo_password';</li>
		<li>CREATE DATABASE data_testing</li>
		<li>CREATE TABLE tablename(field varchar(255),number int)</li>
	</ol> 
	
3) After the sample database is setup follow this tutorial from heroku. [https://devcenter.heroku.com/articles/getting-started-with-rails4]
