Terminal Command step by step
1. npm init -y
2. npm i --save-dev prisma typescript ts-node @types/node nodemon
3. //initialize prisma | npx prisma init --datasource-provider postgresql

to migrate prisma database after done making changes
4. npx prisma migrate dev --name init

install client library
5. npm i @prisma/client 
6. npx prisma generate 

7. after done declaring everything in schema.prisma
npx prisma migrate dev

CRUD operations
create
8. npx prisma generate 