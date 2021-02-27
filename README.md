# Docker & PHP 
Se crea un archivo Dockerfile
versión `php:7.4-apache`
<hr>
Creamos la imagen en base al dockerfile

```docker build -t hello-php .```

Creamos el contenedor a partir de la imagen

```docker run -p 8085:80 hello-php```

Desde el navegador ejectuar
```localhost:8085``` :rocket:



