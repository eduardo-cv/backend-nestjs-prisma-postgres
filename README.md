# backend-nest-prisma-postgres
Modelo Backend em NestJS com Prisma e Postgres

Escolher o pacote de sua preferencia.

npm install

ou

yarn

ou

pnpm install


criar um arquivo  .env

DATABASE_URL="postgresql://postgres:password@localhost:5432/meudb?schema=public"


Uma das formas de gerar o schema automáticamente é usar os seguintes comandos.

'''
prisma introspect

prisma generate
'''
