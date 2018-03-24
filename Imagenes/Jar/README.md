docker build -t javier/jar2  .
docker run --name prueba2 -it --rm d779250388f1 bash
java -jar PrivaliaSpringProject-0.0.1-SNAPSHOT.jar