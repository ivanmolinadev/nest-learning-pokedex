<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

# Ejecutar en desarrollo

1. Clonar el reporsitorio
2. Ejecutar

```
yarn install
```

3. Tener nest Cli instalado

```
npm i -g @nestjs@cli
```

4. Levantar la base de datos

```
docker-compose up -d
```

5. Clonar el archivo `.env.template` y renombrar la copia a `.env`

6. Llenar las variables de entornos definidas en el .env

7. Ejecuta la aplicacion en dev:

```
yarn start:dev
```

8. Reconstruir la base de datos con la semilla

```
http://localhost:3001/api/v2/seed
```

# Stack usado

- MongoDB
- NEST
