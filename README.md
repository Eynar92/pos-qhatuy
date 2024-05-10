# Descripción

## Correr en dev

1. Clonar el repositorio
2. Instalar dependencias `pnpm i`
3. Crear una copia del archivo `.env.template` y renombrarlo por `.env` y cambiar las variables de entorno.
4. Levantar la base de datos `docker compose up -d`
5. Correr las migraciones de Prisma `pnpm prisma migrate dev`
6. Correr el proyecto `pnpm run dev`