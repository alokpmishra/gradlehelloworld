# gradlehelloworld
this is sample project for hello world program using gradle

To run gradle on Centos or any linux machine you need jdk
##Install JDK
sudo yum -y install java-1.8.0-openjdk wget unzip

##Install gradle in the centos machine to create project in gradle
wget https://services.gradle.org/distributions/gradle-4.10.2-bin.zip
sudo mkdir /opt/gradle
sudo unzip -d /opt/gradle gradle-4.10.2-bin.zip
export PATH=$PATH:/opt/gradle/gradle-4.10.2/bin

#Initialize a New Java Project and Create HelloWorld.java
(It will create sample gradle project delete files in src/main/java and src/test/java)
this sample project create using below command need not to execute 
gradle init --type java-library

#Create file vi src/main/java/com/happy/learning/demo/HelloWorld.java
mkdir -p src/main/java/com/happy/learning/demo
touch HelloWorld.java

gradle tasks
gradle assemble
gradle build
build\libs jar will be there



