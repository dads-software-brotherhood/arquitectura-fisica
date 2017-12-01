# Instrucciones

## Generación del Aplicativo

1. Ingresar a la siguiente url [Kukulkan App Generator](http://200.38.177.199:8080/)
2. Ingrese en `Account -> Sign` In e ingrese las siguientes credenciales
```sh
  user: admin
  password: admin
```
3. A continuación dirijase a `Tools->Domain Modeler` y comience a modelar su aplicación.
4. Al terminar de modelar con `DSL-kukulkan` copie modelo y guardelo en un lugar que le permita volver a recuperarlo: por ejemplo, block de notas.
5. A continuación dirijase a `Tools->Grammar Generator` .
6. A continuación copie y pegue su modelo (texto) en el editor blanco, después de clic en el botón `GENERATE APP` revise la consola de salida por si encuentra errores. Esta acción puede tardar un tiempo, debido a que se genera la aplicación completa y pesa más de 125 MB. 
7. Sí no hubo errores, a continuación aparecerá un link con la url de descarga de su aplicativo y el código generado, dar clic en el link para comenzar a descargar.

## Instalación de componentes

El aplicativo está compuesto de la siguiente tecnología:

1. MongoDB -> Requiere Instalación Local
2. Java 8  -> Requiere Instalación
3. Docker  -> (Opcional)
4. Spring Boot
5. Angular 1.5.8
6. Maven 

Con la finalidad de ejecutar el aplicativo, al menos es necesario contar con la version mas reciente de **Java JDK 8* y **MongoDB**. A continuación se dejan los links en los que encontrará cómo instalar dichos paquetes:

1. [Java JDK 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
2. [MongoDB](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows/)

Al terminar de instalar los paquetes necesarios, se deberá de agregar la variable de ambiente `JAVA_HOME` y agregar a su variable `PATH` de su sitema operativo. A continuación se dejan unos links en los que encontrará instrucciones detalladas de acuerdo con el sistema operativo que esté utilizando:


