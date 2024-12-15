# CRUD API Java - Spring Boot - JPA - MySQL

![Logo](https://img.shields.io/badge/Java-Spring%20Boot-blue)
![License](https://img.shields.io/badge/license-MIT-green)

Una API RESTful construida con **Java**, **Spring Boot**, **JPA** y **MySQL** para realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) en una base de datos.

Esta API maneja el registro de personas, con campos como `nombre` y `telefono`, y proporciona un conjunto de rutas para interactuar con estos datos.

## Tabla de Contenidos

- [Descripción](#descripción)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Instalación y Configuración](#instalación-y-configuración)
- [Uso](#uso)
- [Rutas de la API](#rutas-de-la-api)
- [Pruebas](#pruebas)
- [Licencia](#licencia)
- [Contribución](#contribución)

## Descripción

Esta API permite realizar las operaciones CRUD básicas sobre un recurso de `Persona` almacenado en una base de datos MySQL. El proyecto utiliza **Spring Boot** para crear la API REST y **JPA** para interactuar con la base de datos.

**Funcionalidades de la API**:
- Crear nuevas personas.
- Obtener la lista de personas registradas.
- Modificar la información de una persona.
- Eliminar personas del registro.

La API está diseñada para ser escalable y fácilmente extendible para agregar más funcionalidades en el futuro.

## Tecnologías Utilizadas

- **Java 17** (o superior)
- **Spring Boot 2.x**
- **Spring Data JPA**
- **MySQL** (Base de datos)
- **Lombok** (para reducir el código repetitivo)
- **Maven** (como gestor de dependencias)

## Instalación y Configuración

### Prerrequisitos

1. **Java** 17 o superior.
2. **MySQL** instalado y corriendo.
3. **Maven** instalado (para compilar el proyecto).

### 1. Clonar el Repositorio

Clona el repositorio en tu máquina local:

```bash
git clone https://github.com/tuusuario/CRUD-Java-JPA-Spring-Boot-MySQL.git
