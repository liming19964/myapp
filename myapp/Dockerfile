FROM java:8
ARG JAR_FILE
COPY target/${JAR_FILE}  myapp.jar
ENTRYPOINT ["java", "-jar" , "/myapp.jar"]