# ventas-etl
Primer ETL en Python con un Dataset de ventas

## Ejecución
Primero iniciamos la base de datos con Docker Compose:

```
docker-compose up
```

Para construir la imagen del ETL:

```
docker build -t imagen-python-primer-etl .
```

Para ejecutar la imagen:

```
docker run --name container-python-primer-etl -p 8080:8080 -d imagen-python-primer-etl
```

