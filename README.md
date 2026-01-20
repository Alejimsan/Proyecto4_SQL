# Proyecto 4: SQL - Análisis de Datos de Aerolíneas

Este repositorio contiene la solución práctica al módulo de SQL. El objetivo principal es realizar consultas de lectura (DQL) sobre una base de datos relacional compleja para extraer información relevante sobre vuelos, reservas y aviones.

##  Estructura del Proyecto

* `IntroBBDD.sql`: Archivo SQL que contiene todas las consultas resueltas (ejercicios obligatorios y opcionales).

##  Instalación y Requisitos

Para ejecutar estas consultas, se ha utilizado la base de datos de demostración de **PostgreSQL** ("Bookings").

1.  **Motor de Base de Datos:** PostgreSQL.
2.  **Fuente de Datos:** 
    * [Postgres Pro Demo Database](https://postgrespro.com/docs/postgrespro/current/demodb-bookings-installation.html)

##  Ejercicios Resueltos

Las consultas incluidas en el archivo `IntroBBDD.sql` resuelven los siguientes planteamientos:

### Consultas Principales
1.  **Vuelos a tiempo:** Recuperación de vuelos (`flight_id`, `flight_no`) con estado 'On Time'.
2.  **Reservas de alto valor:** Extracción de reservas (`bookings`) con un importe total superior a 1.000.000 de rublos.
3.  **Flota de aviones:** Listado de modelos de aviones disponibles en la tabla `aircraft_data`.
4.  **Vuelos Boeing 737:** Identificación de vuelos realizados con el código de avión `733`.
5.  **Pasajeros "Irina":** Información detallada de tickets comprados por pasajeros cuyo nombre comienza por "Irina".

### Consultas Opcionales (Avanzadas)
6.  **Ciudades con múltiples aeropuertos:** Detección de ciudades que cuentan con más de un aeropuerto.
7.  **Vuelos por modelo:** Conteo del número de vuelos agrupados por modelo de avión.
8.  **Reservas grupales:** Identificación de reservas (`book_ref`) que incluyen más de un billete (varios pasajeros).
9.  **Retrasos significativos:** Listado de vuelos con un retraso en la salida superior a 1 hora.

##  Cómo usar este repositorio

1.  Clona el repositorio en tu máquina local.
2.  Abre el archivo `IntroBBDD.sql` en tu editor de código (VSCode, DBeaver, pgAdmin).
3.  Ejecuta las sentencias sobre tu instancia local de la base de datos `demo`.
