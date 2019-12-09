FROM java:8
MAINTAINER pb
ADD ifast-1.0.0.jar app.jar
EXPOSE 8088
CMD java -jar app.jar --spring.profiles.active=dev
