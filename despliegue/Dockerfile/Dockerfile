# ------------------------------------------------------------------------
#
# Directorio de ubicacion de todos los microservicio /opt/<NOMBRE>
#
# docker build -f Dockerfile -t conexion-renova-prueba .
# 
# ------------------------------------------------------------------------

FROM openjdk:11-jre-slim-buster
RUN apt-get update && apt-get install curl -y
COPY ./src/conexion-renova-prueba.jar /opt/microservice/conexion-renova-prueba.jar
ENTRYPOINT ["java","-jar","/opt/microservice/conexion-renova-prueba.jar"]