# Sistema de Facturación MVC

## Datos del estudiante

**Nombre:** Rene Abraham Pirir  
**Carné:** 7690-23-22174  

## Descripción

Aplicación web desarrollada con arquitectura **Modelo-Vista-Controlador (MVC)** para la gestión de información de un sistema de facturación.

El proyecto implementa cuatro módulos:

- Clientes
- Empleados
- Marcas
- Puestos

Cada módulo permite registrar y visualizar información almacenada en MySQL.

## Arquitectura MVC

El proyecto separa las responsabilidades de la siguiente forma:

- **Modelo:** clases de dominio como Cliente, Empleado, Marca, Persona y Puesto.
- **DAO:** acceso y operaciones sobre la base de datos MySQL.
- **Controlador:** Servlets que reciben las peticiones, procesan la información y coordinan el flujo hacia las vistas.
- **Vista:** páginas JSP estilizadas con Bootstrap.

## Tecnologías utilizadas

- Java
- Jakarta EE 10
- Servlets
- JSP
- Maven
- Apache Tomcat 10.1
- MySQL
- Bootstrap 5.3

## Funcionalidades

### Clientes
- Registrar clientes.
- Mostrar clientes registrados.

### Empleados
- Registrar empleados.
- Seleccionar un puesto existente.
- Mostrar el ID y nombre del puesto asignado.
- Mostrar empleados registrados.

### Marcas
- Registrar marcas.
- Mostrar marcas registradas.

### Puestos
- Registrar nuevos puestos.
- Mostrar puestos disponibles.
- Utilizar los puestos registrados en el módulo de empleados.

## Diseño

Las vistas utilizan Bootstrap para incluir:

- Barra de navegación.
- Formularios responsivos.
- Botones estilizados.
- Tablas responsivas.
- Alertas de registro exitoso o error.
- Diseño consistente entre los módulos.

## Base de datos

Base utilizada:

`sistema_facturacion`

La aplicación utiliza MySQL en el puerto configurado en `ConexionBD.java`.

La contraseña no se almacena directamente en el código. Se obtiene mediante la variable de entorno:

`MYSQL_PASSWORD`

## Ejecución

1. Abrir el proyecto Maven en Apache NetBeans.
2. Configurar Apache Tomcat.
3. Verificar la conexión a MySQL.
4. Definir la variable de entorno `MYSQL_PASSWORD`.
5. Ejecutar **Clean and Build**.
6. Ejecutar **Run**.
7. Abrir la aplicación desde la URL generada por Tomcat.

## Video de demostración

**Enlace del video:** https://drive.google.com/file/d/1UK-RWDQ5zu7UxwZ6BKEXnevrpIAaEL35/view?usp=sharing

El video muestra la arquitectura MVC, el diseño con Bootstrap y el funcionamiento de los módulos principales.

## Autor

**Rene Abraham Pirir**  
**Carné:** 7690-23-22174
