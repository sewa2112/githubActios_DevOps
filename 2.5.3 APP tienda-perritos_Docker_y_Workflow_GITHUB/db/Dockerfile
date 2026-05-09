# Imagen base MySQL 8 oficial
FROM mysql:8


COPY init.sql /docker-entrypoint-initdb.d/
EXPOSE 3306

# Copiar el script de inicialización dentro de la imagen
# Se ejecuta automáticamente la primera vez que se levante el contenedor
COPY init.sql /docker-entrypoint-initdb.d/

# Exponer el puerto de MySQL
EXPOSE 3306
