## Garaje Code Pills - API Consumer
Esta aplicación en Java realiza una solicitud HTTP GET a una API externa para obtener y mostrar información específica. Utiliza la biblioteca JSON.simple para parsear la respuesta JSON.

### Requisitos
- Java Development Kit (JDK) 8 o superior
- Biblioteca JSON.simple

### Instalación

- Clonar el repositorio:

`git clone https://github.com/tu-usuario/garaje-code-pills-api-consumer.git
cd garaje-code-pills-api-consumer`

- Agregar la biblioteca JSON.simple:

Descarga el archivo JAR de JSON.simple desde [JSON.simple](https://mvnrepository.com/artifact/com.googlecode.json-simple/json-simple/1.1) en Maven y colócalo en el directorio lib.

- Compilar el proyecto:

`javac -cp lib/json-simple-1.1.1.jar src/main/garaje/pills/Main.java -d bin`

- Ejecutar la aplicación:

`java -cp "lib/json-simple-1.1.1.jar:bin" main.garaje.pills.Main`

Al ejecutar la aplicación, esta realizará una solicitud HTTP GET a la API de JSONPlaceholder para obtener un post específico (en este caso, el post con ID 1) y mostrará el contenido del cuerpo del post en la consola.
