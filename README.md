<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest


# Product Microservice

## Dev
1. Clonar el repositorio
```bash
$ git clone 'https://github.com/Nest-Miscroservices/products-microservices.git'
````

2. instalar de pendencias
```bash
$ npm install
```
3. Crear un archivo `.env` en la raiz del proyecto basado en el archivo `.env.template`

4. Ejecutar migraciones de prisma `npx prisma migrate dev`

5. Ejecutar el proyecto
```bash
$ npm run start:dev
```
