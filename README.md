npx create-next-app@latest

npm i @prisma/client

npm i -D prisma

npx prisma init --datasource-provider sqlite

npm prisma migrate dev --name init

npx prisma generate
