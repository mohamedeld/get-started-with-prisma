npm i --save-dev prisma typescript ts-node @types/node nodemon

npx prisma init --datasource-provider postgresql

npx prisma format

npx prisma migrate dev --name init

npm i prisma/client

npx prisma generate
