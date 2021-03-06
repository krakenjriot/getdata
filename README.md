# Get Data from Cloud  

## Setup and configurations  

Download and Install the following Applications to your desktop  
* <a href="https://atom.io/">ATOM Text Editor</a>
* <a href="https://www.apachefriends.org/index.html">XAMPP</a> (PHP & Mysql)
* <a href="https://desktop.github.com/">Github Desktop</a>

Once completed, proceed on below steps

**Clone the repository**  
  
<img src="https://github.com/krakenjriot/images/blob/master/getdata/7.JPG" width=800 />  

**Click open in desktop**  
  
<img src="https://github.com/krakenjriot/images/blob/master/getdata/8.JPG" width=800 />  

  
**Click open URL**  
  
<img src="https://github.com/krakenjriot/images/blob/master/getdata/9.JPG" width=800 />  
 
Github Desktop application will open at this moment, wait...  
make sure the LOCAL PATH is set to c:\xampp\htdocs\getdata  
**Click Clone**  
  
<img src="https://github.com/krakenjriot/images/blob/master/getdata/10.JPG" width=800 />  

**Click Show in Explorer**  
  
<img src="https://github.com/krakenjriot/images/blob/master/getdata/11.JPG" width=800 />  

**Verify files (make sure you have all the shown files)**  
  
<img src="https://github.com/krakenjriot/images/blob/master/getdata/12.JPG" width=800 />  

**before running the data downloader scheduler page**
  
*Noted! we need to update the CiD and Site Code with yours in the getdata.exec.php file first!*

**Right click and edit**  
**( open it on any text editor / notepad would be fine / mine I used notepadd++ )**
  
<img src="https://github.com/krakenjriot/images/blob/master/getdata/13.JPG" width=800 />  
  
**Update your CiD and Site Code**  
**Right click and edit "getdata.exec.php"**  
  
<img src="https://github.com/krakenjriot/images/blob/master/getdata/14.JPG" width=800 /> 
  
**Get your CiD and Site Code from the KJR Application**
  
<img src="https://github.com/krakenjriot/images/blob/master/getdata/15.jpg" width=800 /> 
  
if you don't have the application yet in your mobile, please download it from *Google App Store* at 
<a href="https://play.google.com/store/apps/details?id=com.internetofthingsbuilder.switchmaster.boaz">KJR IoT App</a> 
and register and register your new arduino board and go back <a href="https://github.com/krakenjriot/getdata">here</a>
  
  
  


**NEXT STEPS IS TO PREPARE THE DATABASE THAT WILL RECIEVE YOUR CLOUD DATA**
  
 Open XAMPP and make sure the PHP and MySQL are started and running green
 <img src="https://github.com/krakenjriot/images/blob/master/getdata/16.jpg" width=800 /> 
  
**Open http://localhost/phpmyadmin/ (PHPMyAdmin) on the browser**  
* <a href="http://localhost/phpmyadmin/">http://localhost/phpmyadmin/</a>

  
<img src="https://github.com/krakenjriot/images/blob/master/getdata/19.JPG" width=800 /> 


**Create a new database, with a name of "mydb" (make sure you create with that name)**
  
<img src="https://github.com/krakenjriot/images/blob/master/getdata/20.JPG" width=800 /> 

**PREPARING THE TABLE**

**Select the database you created (mydb) and then click the Import button on the top middle of your screen**
  
<img src="https://github.com/krakenjriot/images/blob/master/getdata/21.JPG" width=800 /> 


**browse the downloaded table file and initiate import**
 
<img src="https://github.com/krakenjriot/images/blob/master/getdata/21.JPG" width=800 /> 
  
<img src="https://github.com/krakenjriot/images/blob/master/getdata/22.JPG" width=800 /> 
  
<img src="https://github.com/krakenjriot/images/blob/master/getdata/23.JPG" width=800 /> 
  
<img src="https://github.com/krakenjriot/images/blob/master/getdata/24.JPG" width=800 /> 
  
<img src="https://github.com/krakenjriot/images/blob/master/getdata/25.JPG" width=800 /> 

<img src="https://github.com/krakenjriot/images/blob/master/getdata/26.JPG" width=800 /> 

**RUNNING THE DATA DOWNLOADER PAGE**

**Open your browser (preferably Google Chrome) copy paste this or click this link http://localhost/getdata/getdata.php **
  
you would know if it is successfull, there should be no error message same as below
  
<img src="https://github.com/krakenjriot/images/blob/master/getdata/17.JPG" width=800 />    


*THE END* 



  
  
  