# *SOFTWARE DE PEDIDOS RESTAURANTE*
**Realizado con java y el framework de spring boot versiones:**
- Java version "17.0.6" 2023-01-17 LTS
- id 'org.springframework.boot' version '3.2.3'

**Dependencias utilizadas son:**
1. Spring Web: Soporte para el desarrollo de aplicaciones y páginas webs basadas en Java
2. JPA: API de persistencia desarrollada para la plataforma Java EE. Maneja datos relacionales en aplicaciones usando la Plataforma Java.
3. MySQL driver: Permite comunicarnos con el motor de base de datos,
4. Lombok: librería para Java que proporciona anotaciones y funciones para reducir la cantidad de código (ejemplo getters and setters)


## Conexion a BD y ejecucion del proyecto
Mediante la siguiente ruta (**src\main\resources\application.properties**) se debe configurar unicamente el username y contraseña de acuerdo a su MySQL ya que si las credenciales no son las correctas se generara un error de conexion con la base de datos.

## Conexion a BD y ejecucion del proyecto
Mediante la siguiente ruta (**src\main\resources\application.properties**) se debe configurar unicamente el username y contraseña de acuerdo a su MySQL ya que si las credenciales no son las correctas se generara un error de conexion con la base de datos.
Despues de realizar esto, para la ejecucion se debe estar parado en la clase (**src/main/java/com/asandoval/restaurante/RestauranteApplication.java**) donde esta realizara la creacion de la base de datos con sus respectivas tablas. 

## Url
localhost:8081/index.html
