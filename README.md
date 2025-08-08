<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

# Product  Microservice

## Dev

1. Clonar el repositorio
2. Instalar dependencias
3. Crear un archivo `.env` basado en el `.env.template`
4. Ejecutar migraciones de prisma `npx prisma migrate dev`
5. Levantar el servicio de Nats `docker run -d --name nats-server -p 4222:4222 -p 6222:6222 -p 8222:8222 nats`
6. Ejecutar el proyecto `npm run start:dev`
