# onlineData
In this project a simple mobile hybrid application can access an online data. It allows sharing of data among different mobile app users. It does not follow a REST approach, but is only a basic implementation. Database runs on mysql which is accessed by a php script. The hybrid app takes the form of a simple html page.
Folder onlineData must be under htdocs folder of your Apache server.
It conaints the index.php file which can access the database and the sub-folder db contains the sql script to create the table.

Start your XAMPP server
1.Creating the database
1.1create a database 'mybookstore' under mysql (through phpmyadmin interface)
1.2then import the script bookstore.sql which will create the books table

2. Ensure that the onlineData folder is in the htdocs folder of Apache

3. Create your hybrid project (phonegap desktop app may be used to create the project)
3.1 under the www folder, replace the index.html with the one provided
You may open the index.html without creating the phonegap desktop app project.

