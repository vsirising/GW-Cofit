13.2 Web Application Instruction

13.2.1 Setting Up mysql database
Since our web application is still a prototype, you can only run it on a local server. You will have to use XAMPP to create a  mysql database (https://www.apachefriends.org/index.html). After you install XAMPP on your computer,  you will go to PHPmyAdmin to create your database. The database should be called “ gw cofit”(Make sure that it is exactly as the picture below). After creating the database you can import the “gw_cofit.sql” file to create all the tables and insert all of the test data. 

13.2.2 Running Web Application on localhost
To run applications on localhost, you need to create a folder called “gwcofit” in the folder “htcdocs”, which is located in your xampp folder. You will have to download all the files and folders from Github and put them into your gwcofit folder. After this step, go to your browser and type in “http://localhost/gwcofit/index.php” (make sure that both Apache and MySQL is running on XAMPP. Also, beware Mac users might have some issues with XAMPP.).

13.2.3 Creating a Users and Log In 
Once you finish up with running the web applications on localhost and find that it is working properly, You will have to do do the following steps as a User by using  these links (“http://localhost/gwcofit/registration.php”/“http://localhost/gwcofit/instructorregistration.php”)
1.As a new User sign up for the USER account that you prefer ( Students/GW Instructor)
2.Once You click the sign up button a pop up will appear and that will enable you to fill in the registration information that is required
3.After submitting the registration, all that would be required from you is to, select your account type and then fill out your Username and Password in the “Log In” text box found on the navigation bar above
4. After logging in, you will be directed to your Dashboard and will be able to use our system

13.2.4 Creating Admin User
You can only create an admin user through a file call “adminregistration.php”. which is not connected to the main web application. You can type in “http://localhost/gwcofit/adminregistration.php” in your web browser. After you put in all the information and click sign up, all the information will be submitted to the database and can be used to log into the system (Make sure you select Admin on the user type dropdown while logging in)

13.2.5 Upload Contents
As a Instructor Account, you have the ability to upload the contents for the students. After you log into the system you will see the dashboard where you can select which type of contents you want to upload. Click the Upload button to upload your video (The maximum upload file size is 500 MB). Fill out the description of the video and click upload. The video will be uploaded and stored in the folder cardio/strength/yoga (depending on the type of  content you choose to upload). Once you have uploaded the video, it will be displayed on the content dashboard.


13.2.6 Admin Content and Account Management
As an Admin, you will be able to edit and delete both the student account, instructor account and contents. If you want to edit or delete an account, click on the edit students account or edit instructor account on the dashboard. If you want to edit or delete any content, click on the edit contents dashboard. 


13.2.7 Username and Password sample (can be use to log into the system right away)
Student (username: studenttest1 | Password : studentpassword1)
Instructor (username: instructortest1| Password : instructorpassword1)
Admin:(username: Admintest2 | Password:adminpassword2)
