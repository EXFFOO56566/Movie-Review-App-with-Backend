# Movie-Review-App-with-Backend
How to Configure Webservice In Your Server? - top
First of all find the Php Code(movie_review_app) folder from the downloaded package.
Copy these folder and paste it in the htdocs folder(if you have Wampp installed then put it into www)
Then create a database and import the database from the db folder.
Aftre creating database configure the connection file,which is in the includes folder of your package.
$serverIp="localhost";
$userName="root";
$password="";
$dbname="movie_review_app";
That’s all,now run the webservice : http://localhost/movie_review_app/index.php
Login Details
Username: admin   Password: admin

Where to put Server Url in Application? - top

Select Project > go to com.example.util package > Constant.java Class
Open Constant.java
now if your Sever is http://abc.com so your service url like that http://abc.com/api.php and image path http://abc.com/images
