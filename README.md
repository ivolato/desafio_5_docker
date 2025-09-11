# Docker + docker-compose
Este trabajo tiene como objetivo desarrollar un build en docker y configurar un entorno
local para que corra una aplicación de nestjs con docker-compose.


## Clonar el repositorio.
```
git clone https://github.com/ivolato/desafio_5_docker.git
```

## Creamos la imagen, el contenedor para la DB y el contenedor de NestJS.
```
cd desafio_5_docker
docker-compose up -d --build
```



