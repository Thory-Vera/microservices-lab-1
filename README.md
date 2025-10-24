Microservices Lab

Laboratorio práctico de microservicios usando Django y React.

🏗 Arquitectura del proyecto

El proyecto está dividido en varios servicios independientes:

auth-service/ → Manejo de autenticación y generación de tokens JWT

blog-service/ → Gestión de publicaciones, autores y categorías

email-service/ → Envío de notificaciones y formularios

frontend/ → Interfaz web desarrollada en React

reverse-proxy/ → Gateway local y balanceo de solicitudes

🧩 Servicios auxiliares

PostgreSQL: Base de datos principal (puerto 5432)

Redis: Caché y almacenamiento temporal (puerto 6379)

🧪 Reto práctico de hoy

Levantar todos los contenedores:

docker compose up -d


Crear un script de prueba de conexión en auth-service/test_connection.py para PostgreSQL y Redis.

Ejecutar el script dentro del contenedor correspondiente:

docker exec -it <nombre_contenedor> python test_connection.py

✅ Estado del proyecto

 Estructura de carpetas inicial configurada

 Repositorio Git y GitHub preparados

 Docker Compose funcional

 Documentación básica en README
