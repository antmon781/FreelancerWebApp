# FreelancerWebApp

This is a web application that allows artistic professionals to offer their services to users willing to pay for them. Talented individuals will be able to share or create a visual portfolio within the application for potential customers to view. 

/* Setting up the environment for Kreative Web Application

author: Antonio Monteiro @ Platform by Per Scholas */

Importing:
Project is saved in an Eclipse Archive File.

MariaDB:
1. In persistence.xml file in '/Java Resources/META-INF/', make sure port number matches mariaDB on your local machine. Currently it is set to "3306"

2. Correct user and password property in persistence.xml file. Currently it is set to "root" and "password"

UserServices Class:
1. In the current iteration, user directories location path is hard-coded.
You will need to go to UserServices.java file in com.kreative.services package and make a change to the method "createUserDirectory"

2. In the constructor of File object on line 233, please change the absolute path of users folder in eclipse-workspace to match your local machine. Currently it is set to - 
"C:\\Users\\Antonio\\eclipse-workspace\\.metadata\\.plugins\\org.eclipse.wst.server.core\\tmp0\\wtpwebapps\\CaseStudySpring\\resources\\users\\" 




