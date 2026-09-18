# Práctica: Exploración de Datos con PostgreSQL y Chinook DB

## Requisitos del Sistema

## Variante y Origen de la Base de Datos

* **Variante:Chinook_PostgreSql_SerialPKs.sql (Usa llaves primarias con SERIAL).
* **Origen: [Repositorio Oficial de Chinook DB](https://github.com/lerocha/chinook-database) / Material de curso Semana 9.
* **Nombre de la base de datos: chinook_serial

## Estructura del Repositorio
text
├── docker-compose.yml   # Configuración del servicio PostgreSQL en Docker
├── .env.example         # Plantilla de variables de entorno (sin secretos)
├── .gitignore            # Exclusión de credenciales y volúmenes locales
├── README.md            # Documentación e instrucciones de ejecución
└── consultas.sql        # Script con los 10 apartados obligatorios
