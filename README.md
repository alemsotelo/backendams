Portfolio Web - #YoProgramo
Descripción
Backend del Portfolio Web Fullstack realizado como Proyecto Final del curso Argentina Programa - #YoProgramo.

Se trata de una API REST realizada utilizando las tecnologías Java + Spring Boot bajo el modelo MVC para la lógica y MySQL para persistencia de datos.


⌨🖱 Instalación
Si queremos correr la aplicación en un entorno local debemos tener en cuenta lo siguiente:
Clonar el repositorio utilizando GIT o descargando el archivo ZIP:

git clone https://github.com/alemsotelo/backendams.git

Instalar las dependencias de Maven utilizando nuestro IDE preferido o a través del comando:

mvn install

Crear/Configurar el archivo application.properties en src/main/resources/

# Ambiente de prueba (local)
spring.jpa.hibernate.ddl-auto = update
spring.datasource.url = jdbc:mysql://<host_DB>:<puerto_DB>/<nombre_DB>?useSSL=false&serverTimezone=UTC
spring.datasource.username = <usuario>
spring.datasource.password= <contraseña>
spring.jpa.database-platform = org.hibernate.dialect.MySQL8Dialect
#JWT
portfolio.jwtSecret = <clave_alfanumérica_JWT>
portfolio.jwtExpirationMs = <tiempo_expiración_JWT> 
NOTA: Reemplazar los valores borrando los <>.

Ejecutar nuestra aplicación iniciando el archivo PortfolioApplication.Java o bien ejecutando el siguiente comando: mvn sprin-boot:run
