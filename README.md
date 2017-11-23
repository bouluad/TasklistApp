# tasklist-service
Example microservice for showing tasks.

## Maven
Build it with `mvn install`. You can run it with `java -jar target/tasklist-service-1.0-SNAPSHOT.jar server tasklist-service.yml`.

## Docker
Build the image it with `docker build -t tasklist .`. You can run the container `docker run -it tasklist`, than `docker inspect <CONTAINERID>`, get adress IP and Port.
