# Proyecto de Computación en la nube

Proyecto realizado utilizando la aplicación de código abierto limesurvey para desplegar dicho servicio con alta disponibilidad y tolerancia a fallos.

# Variables de entorno

| Parameter      | Description                                                      |
| -------------- | ---------------------------------------------------------------- |
| DB_HOST        | Database server hostname                                         |
| DB_NAME        | Database name                                                    |
| DB_USERNAME    | Database user                                                    |
| DB_PASSWORD    | Database user's password                                         |
| ADMIN_NAME     | Initial LimeSurvey Admin Name                                    |
| ADMIN_EMAIL    | Initial LimeSurvey Admin Email                                   |
| ADMIN_USER     | Initial LimeSurvey Admin Username (for signing into admin panel) |
| ADMIN_PASSWORD | Initial LimeSurvey Admin Password (for signing into admin panel) |

## Para iniciar el proyecto

```
docker-compose up -d
```

```
# Frontend
http://localhost:8080/

# Backend
http://localhost:8080/index.php/admin
```

## Referencias:

### [Repositorio de referencia](https://github.com/martialblog/docker-limesurvey)

### [Documentación de Limesurvey](https://www.limesurvey.org/manual/)
