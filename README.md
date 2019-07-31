# Curso de Docker en Platzi

Ésta es una aplicación de ejemplo para el curso de Docker de Platzi por Guido
Vilariño.

Encuentra más información en https://platzi.com, suscríbete al curso y aprende
a usar Docker de manera profesional.

## Comandos

> Docker network create --attachable platzinet

> Docker network ls

> docker run -d --name db mongo

> docker network connect platzinet db

> docker network inspect platzinet

> docker run -d --name app -p 3000:3000 --end MONGO_URL=mongodb://db:27017/test platziapp

> docker network connect platzinet app
