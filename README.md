# Clonar el repositorio

`git clone https://github.com/KarloPry/backend-workshop`

Si no tenemos git descargado, podemos obtenerlo [aqui](https://git-scm.com/downloads)
Y para descargar docker podemos con este link [here] (https://www.docker.com/products/docker-desktop/)

# Comandos de docker

Construimos primero nuestra imagen

Mac / Linux
`sudo docker build -t nest-app .`
Windows
`docker build -t nest-app .`

Y ahora creamos nuestro contenedor

Mac / Linux
`sudo docker run -p 4000:4000 --name my-nest-container nest-app`
Windows
`docker run -p 4000:4000 --name my-nest-container nest-app`

