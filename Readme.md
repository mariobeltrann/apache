## Añade un DNS al docker-compose (puedes usar el que ya tienes)

configuracion completa del docker-compose incluyendo el DNS:

![docker compose entero](./imagenes/dockercompose.png)

## Utiliza docker-compose para configurar las IP fijas a los dos contenedores
configuracion ip fija del primer contenedor:

![configuracion ip fija del primer contenedor](./imagenes/ip.png)


configuracion ip fija del segundo contenedor:

![configuracion ip fija del segundo contenedor](./imagenes/ip1.png)


configuracion ip fija del tercer contenedor:

![configuracion ip fija del tercer contenedor](./imagenes/ip2.png)

## El DNS tiene que resolver dos dominios a la ip del apache:

resuelve el primero

![1](./imagenes/resuelve1.png)

resuelve el segundo

![2](./imagenes/resuelve2.png)

## Prueba a utilizar la directiva DirectoryIndex

![directoryIndex](./imagenes/index.png)

DirectoryIndex se utiliza para seleccionar un fichero html que no es el fichero que se abriría por defecto , es decir , index.html

## Configura dos virtual-host separados para cada dominio en el mismo puerto (80)

![conf hosts](./imagenes/hosts.png)