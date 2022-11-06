FROM adoptopenjdk/openjdk11:alpine-jre
ADD target/springboot-k8s-Cust-mysql-0.0.1-SNAPSHOT.jar cust.jar
ENTRYPOINT ["java","-jar","cust.jar"]