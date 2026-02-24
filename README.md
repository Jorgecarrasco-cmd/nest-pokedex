<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

# Ejecutar en desarrollo

1. Clonar el repositorio
2. Ejecutar 

```
npm install
```

3. Tener nest CLI instalado 

```
npm i -g @nestjs/cli
```

4. Levantar la base de datos

```
docker-compose up -d
```

5. Clonar el archivo __.env.template__ y renombrar la copia a ```.env``` 

6. Llenar las variables de entorno definidas en el .env 

7. Ejecutar la aplicacionn en dev: npm run start:dev

7. Implementar la seed con la data de prueba la base de datos con el siguiente endpoint: 

```
Hacer una peticion get a la ruta http://localhost:3000/api/v2/seed
```
