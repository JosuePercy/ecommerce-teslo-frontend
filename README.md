# Description


## Correr en dev

1. Clonar el repositorio.
2. Crear una copia del ```.env.template``` y renombralo a ```.env``` y cambiar las varialbles 
de entorno.
3. Instalar dependencias ```npm install```
4. Instalar dependencias ```docker compose up -d```
5. Correr las migraciones de Primsa ```npx prisma migrate dev```
6. Ejecutar seed ```npm run seed```
7. Correr el proycto ```npm run dev```

## Correr en prod