WORDPRESS-NGINX SETUP

##

Adding .env parameters for the mysql database.

Step 1:
Create a .env file in the same directory as your compose file

Step 2:
Add the following parameters, updating the password with your choice.

MYSQL_ROOT_PASSWORD=your_root_password
MYSQL_USER=your_wordpress_database_user
MYSQL_PASSWORD=your_wordpress_database_password

Step 3:

If uploading to github, do not forget to edit your .gitignore and include the .env.

The rest will be explained >>>
