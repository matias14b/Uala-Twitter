# Uala-Twitter
Aplicación estilo Twitter para enterarte que pasa en tu red.

# Detalles
### Para clonar el repositorio con sus submodulos, usar:
  > git clone --recurse-submodules https://github.com/matias14b/Uala-Twitter.git

- La aplicación fue construida utilizando mysql. Para fines de simplificar la prueba de los módulos, mysql fue reemplazado por H2.
Si se quiere probar utilizando mysql descomentar las propiedades del application.properties de los módulos Tweet y Usuario.
- Para crear las base en mysql utilizar los schema.sql y data.sql para agregar los datos, estos están en la carpeta Resources.
- Cada modulo contiene su propio readme.md con mas detalles sobre el mismo.
- *Si no toma los applications.properties de cada proyecto, te recomiendo que los abras en ide's separados.

## Casos de uso y la comunicacion entre modulos
### Obtener TimeLine 
![image](https://github.com/matias14b/Uala-Twitter/assets/127508318/534ca6c8-0237-4951-8f84-c0cf3fbe9dcb)

### Seguir a usuario
![image](https://github.com/matias14b/Uala-Twitter/assets/127508318/2bcb3ea5-4977-4eb8-b61f-f8b74f67fb31)

### Obtener tweets
![image](https://github.com/matias14b/Uala-Twitter/assets/127508318/cd0e147d-7483-4eb5-ad1f-d42ad015da6a)

### Crear tweet
![image](https://github.com/matias14b/Uala-Twitter/assets/127508318/72851532-2243-4e79-b112-c10dc8bad066)

### Obtener Usuario con sus seguidores
  ![image](https://github.com/matias14b/Uala-Twitter/assets/127508318/ceb96033-4bfa-4114-91af-8fdc1cff7ceb)

### Obtener Usuario por username
![image](https://github.com/matias14b/Uala-Twitter/assets/127508318/9b0a833a-4eb6-41fb-8360-e8f4f93bc570)



*Diagrama entidad-relación*

![image](https://github.com/matias14b/Usuario-Uala-Twitter/assets/127508318/e65a05f7-4dfd-4b6f-b954-9e6fa5d6c66e)


### Recursos

En la carpeta /doc se encuentra el der, los diagramas de servicios, dominios y la coleccion de postman 
https://github.com/matias14b/Uala-Twitter/tree/30367d03443070db3c50fff6141f0d3a33adbf3d/doc
