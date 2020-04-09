Software and jar files Required:

1) Eclipse IDE for Java EE Developers 
2) Apache Tomcat 8.5 
3) Cisco AnyConnect VPN 
4) ojdbc14.jar 


SetUp Procedure:

1) Extract Eclipse and start. 
2) Extract Apache Tomcat and configure with eclipse.
3) Install Cisco AnyConnect VPN and use this "vpn.gmu.edu" VPN and use netid credentials to get in.
4) Create a table (student642). This can be done in the following way:
 a) Use command line interface.
 b) Use sql GUI.
5) Unzip the 'zip' file: it contains
 - ReadMe file (you are reading this now)
 - 'war' file(created using Export) 
 - 'zip' file(Source code) 
6)  Import the 'war' file to eclipse
 -> file -> import -> filter with 'war'/ select web -> WAR file and click next
 -> browse for this 'war' file -> click finish
7) Run this project
 -> Right click on this project -> 'Run as' -> select 'Run on server'
8) Type the url in the browser (http://localhost:8080/assignment4/SurveyPage.html).
9) Fill in the survey page to proceed in the assignment.


Oracle Table Creation sql query:

create table student642( firstname varchar(25),
 lastname varchar(25),
 SID varchar(25),
 street varchar(50),
 zip varchar(25),
 city varchar(25),
 state varchar(25),
 email varchar(25),
 phone varchar(25),
 url varchar(50),
 dos varchar(25),
 data varchar(50),
 howinterested  varchar(35),
 gradmonth varchar(25),
 year varchar(25),
 likelihood varchar(25),
 mean varchar(25),
 sd varchar(25),
 thingsliked varchar(100),
 comments varchar(100));
