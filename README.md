# Parking App Central Repository
Repositorio central para documentación y coordinación del proyecto de microservicios

Este repositorio central organiza la documentación y las estrategias de desarrollo para la app de estacionamientos basada en microservicios.

## Contenido
- Documentación de arquitectura.
- Estrategia de despliegue.
- Especificaciones API.
- Información sobre los microservicios.

## Microservicios
1. [User Service](./microservices/user-service.md)
2. [Parking Service](./microservices/parking-service.md)
3. [Billing Service](./microservices/billing-service.md)
4. [Notification Service](./microservices/notification-service.md)
5. [Frontend](./microservices/frontend.md)

Documentación Técnica
docs/architecture.md: Detalla la arquitectura del sistema.
docs/deployment-strategy.md: Describe cómo se hará el despliegue de los microservicios.
microservices/*.md: Archivos para documentar cada microservicio con detalles como endpoints, configuraciones y dependencias.
shared/config.md: Define configuraciones comunes para todos los microservicios.
Ejemplo del archivo microservices/user-service.md:
# User Service

## Descripción
Gestiona usuarios, incluyendo autenticación y roles.

## Repositorio
[Repositorio del User Service](https://github.com/tu-usuario/user-service)

## Endpoints
- `POST /users`: Crear un usuario.
- `POST /login`: Iniciar sesión.

## Configuración
- Puerto: `8081`
- Base de datos: `users_table`

