# Next.js OpenJira App
Para correr localmente, se necesita la base de datos.
```
docker-compose up -d
```

* El -d, significa __detached__



## Configurar las variables de entorno
Renombrar el archivo __.env.template__ a __.env__
* MongoDB URL Local:
```
MONGO_URL=mongodb://localhost:27017/entriesdb
```

* Reconstruir los módulos de node y levantar Next
```
yarn install
yarn dev
```


## Llenar la base de datos con información de pruebas

Llamara:
```
http://localhost:3000/api/seed
```


## Contacto

- Nombre: Mariana Trinidad Ardissone
- Correo electrónico: mariana.ardissone7@gmail.com
- GitHub: @Mar_ardissone
- Portfolio: https://mardissone.com.ar/