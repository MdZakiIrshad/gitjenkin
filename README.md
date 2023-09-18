# gitjenkin
In this pipeline script stage one will download java webapplication from git hub .
In the stage two we run mvn clean package to create a .war file after compiling and testing .
In the stage three we build the docker image which will deploy our webapp.
