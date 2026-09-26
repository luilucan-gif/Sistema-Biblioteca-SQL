# 📚 Sistema de Biblioteca Universitaria - SQL Server

Base de datos relacional desarrollada en **Microsoft SQL Server** para gestionar los principales procesos de una biblioteca universitaria.

Este proyecto fue desarrollado como parte de mis prácticas académicas en Ingeniería en Inteligencia Artificial.

## 🎯 Objetivo

Diseñar e implementar una base de datos que permita organizar la información de usuarios, estudiantes, docentes, libros, autores, categorías, préstamos y sanciones de una biblioteca universitaria.

## 🗄️ Base de datos

La base de datos está compuesta por las siguientes entidades principales:

- 👤 Usuario
- 🎓 Estudiante
- 👨‍🏫 Docente
- 📚 Libro
- ✍️ Autor
- 🏷️ Categoría
- 🔗 Libro_Autor
- 📋 Política de préstamo
- 📖 Préstamo
- 📝 Detalle de préstamo
- ⚠️ Sanción

## 🔗 Modelo relacional

El diseño utiliza relaciones entre las diferentes tablas para mantener organizada la información y evitar duplicidad de datos.

Se implementan:

- Claves primarias (Primary Key)
- Claves foráneas (Foreign Key)
- Relaciones entre tablas
- Tabla intermedia para la relación entre libros y autores
- Restricciones de integridad

## ⚙️ Funcionalidades

La estructura permite gestionar:

- Registro de usuarios
- Diferenciación entre estudiantes y docentes
- Registro de libros
- Clasificación por categorías
- Registro de autores
- Relación entre libros y autores
- Gestión de préstamos
- Fechas de devolución pactada y real
- Políticas de préstamo según el tipo de usuario
- Registro de sanciones

## 🛠️ Tecnologías utilizadas

- Microsoft SQL Server
- SQL
- SQL Server Management Studio (SSMS)
- Modelo relacional de bases de datos

## 📁 Archivo principal

`BibliotecaUniversitaria_Restauracion.sql`

Contiene el script necesario para crear y restaurar la estructura de la base de datos.

## ▶️ Ejecución

1. Abrir Microsoft SQL Server Management Studio.
2. Conectarse a una instancia de SQL Server.
3. Abrir el archivo `BibliotecaUniversitaria_Restauracion.sql`.
4. Ejecutar el script.
5. Verificar la creación de la base de datos y sus tablas.

## 🧠 Conocimientos aplicados

Durante el desarrollo del proyecto se aplicaron conceptos de:

- Diseño de bases de datos
- Modelo relacional
- Creación de tablas
- Claves primarias y foráneas
- Relaciones entre entidades
- Integridad referencial
- Consultas SQL
- Gestión estructurada de información

## 👨‍💻 Autor

**Luis Andrés Lucas Reina**  
Estudiante de Ingeniería en Inteligencia Artificial
