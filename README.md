# Instrucciones

## Generación del Aplicativo

1. Ingresar a la aplicación [Kukulkan App Generator](http://200.38.177.199:8080/)
2. Diríjase a `Account -> Sign In` e ingrese las siguientes credenciales:

```sh
  user: admin
  password: admin
```
3. A continuación, diríjase a `Tools -> Domain Modeler` y comience a modelar su aplicación.
4. Al terminar de modelar con el Lenguaje `DSL-kukulkan` copiar el modelo (texto) en un lugar que le permita volver a recuperarlo: por ejemplo, un block de notas.
5. A continuación diríjase a `Tools -> Grammar Generator` .
6. A continuación copie y pegue su modelo (texto) en el editor blanco (primer editor de código), después de clic en el botón `GENERATE APP`; revise la consola de salida por si encuentra errores. Esta acción puede tardar un tiempo, debido a que se genera la aplicación completa y pesa más de 125 MB. 
7. Sí no hubo errores, a continuación aparecerá un link con la url de descarga de su aplicativo y el código generado, dar clic en el link para comenzar a descargar; recordar la ruta en la que se descargó el aplicativo, se utilizará más adelante.

## Instalación de componentes

El aplicativo está compuesto de la siguiente tecnología:

1. MongoDB -> Requiere Instalación Local
2. Java 8  -> Requiere Instalación
3. Docker  -> (Opcional)
4. Spring Boot
5. Angular 1.5.8
6. Maven 

Con la finalidad de ejecutar el aplicativo, al menos es necesario contar con la versión más reciente de **Java JDK 8* y **MongoDB**. A continuación se dejan los links en los que encontrará cómo instalar dichos paquetes de acuerdo con el sistema operativo que esté utilizando:

1. [Java JDK 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
2. [MongoDB](https://docs.mongodb.com/manual/installation/)

Al terminar de instalar los paquetes necesarios, se deberá de agregar la variable de ambiente `JAVA_HOME` para que apunte a su instalación del **Java JDK** . A continuación se dejan unos links en los que encontrará instrucciones detalladas de acuerdo con el sistema operativo que esté utilizando:

1. Para [Windows](https://confluence.atlassian.com/doc/setting-the-java_home-variable-in-windows-8895.html)
2. Para [Linux](https://www.cyberciti.biz/faq/linux-unix-set-java_home-path-variable/)


## Ejecución del Proyecto

Una vez instalado el ambiente de desarrollo, se deberá de dirigir a la carpeta en donde descargó la aplicación generada. Lo anterior deberá de ser desde una línea de consola:

```sh
cd [SU_HOME]/[DOWNLOADED_APP]
unzip [FILE_NAME].zip
cd kukulkanmongo
./mvnw spring-boot:run
```

en dónde `[SU_HOME]/DOWNLOADED_APP]` es la ubicación del aplicativo generado y `[FILE_NAME].zip` es el nombre del aplicativo descargado; este nombre es generado por el servidor.

Al terminar de inicializar el aplicativo podrá ver el aplicativo generado en un navegador web, apuntando a la siguiente **URL**:

```html
http://localhost:8080
```

**¡Kukulkan Generator!**
