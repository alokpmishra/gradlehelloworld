FROM java:8
MAINTAINER alok1rcm@gmail.com
RUN mkdir /javafile
ADD javafile/HelloWorld.java /javafile
WORKDIR /javafile
RUN javac HelloWorld.java
CMD java HelloWorld
