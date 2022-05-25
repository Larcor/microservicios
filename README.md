# microservicios
Autores: Sara Ximena Ortiz Reyes
         Manuel Alejandro Bobadilla
         
Api .Net 3.1
Sql server 2018
Ocelot API Gateway 16.0.1

# Introducción
Esta Api redirecciona dos microservicios los cuales guardan, actualizan y obtiene información de productos y clientes, se utilizó Ocelot para configurar API Gateway, y dos microservicios en .net y una base de datos relacional en sql server

# Instalación 

SDK Net 3.1
Sql server 2018 o superior,
Descargar o clonar el proyecto del respositorio
Crear una migracióm para crear la DB y los objetos de DB
  Ejecutar los siguientes comandos:
    - Add-Migration InitialCreate
    - Update-Database
Configurar los proyectos de inicio como se muestra en la siguiente imagen:
![image](https://user-images.githubusercontent.com/7612153/170155606-034ed4c5-f5cf-4c00-9eb2-f8ffa486e6c0.png)

Ejecutar el proyecto y con ayuda de postman navegar por cada uno de los endpoint por medio del Api gateway

# Arquitectura

![image](https://user-images.githubusercontent.com/7612153/170156561-4c5e7d3f-34fc-45a8-ba87-941c24160824.png)



