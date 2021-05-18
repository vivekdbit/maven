# Apache Maven
---------------------
Maven is a build automation tool used primarily for Java projects.

# Maven for linux installation
---------------------
Yum install maven (centos)
Apt-get install maven (ubuntu)

# Linux 
---------------------
- git clone [https://github.com/vivekdbit/maven]
- mvn install - All the downloaded dependencies will be inside the .m2 folder
- mvn compile 
- cd /root/.m2/repository
- rm -rf repository - Try deleting the repository inside /root/.m2


- All dependencies will be deleted 
- Now let's go back to the maven folder and again run the following
- mvn install - Will install all the dependencies
- mvn package ( will help to package as per the package instruction given inside the pom.xml)
- mvn clean - This will delete the target directory 
- mvn test - This will run all the test cases and gives the summary 
- cd maven - Here you can see pom.xml

# Terminology
---------------------
War- web archive ( compressing all the web application components and arranging them chronologically inside a single war file . like google.war)

Ear - enterprise archive ( compressed version of enterprise application components and arranging them chronologically inside a single ear file . like google.ear)

Jar - java archive  ( compressed version of java application components and arranging them chronologically inside a single jar file . like google.jar)