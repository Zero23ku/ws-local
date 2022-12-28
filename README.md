# WebSphere 8.5 Local

## Modo de uso:

Correr el siguiente comando estando posicionado en la carpeta donde se encuentre docker-compose.yml:
```
docker-compose up -d
```

Una vez levantado el proyecto, ingresar a la siguiente URL:

```
https://localhost:9043/ibm/console/login.do?action=secure
```

**Usuario**: wsadmin


**Para obtener la contraseña es necesario ejecutar el siguiente comando:**
```
docker exec <nombre del contenedor> cat /tmp/PASSWORD
```
**Nota: Para obtener el nombre del contenedor, ejecutar el comando:**
```
docker ps
```
