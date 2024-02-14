validação com zod
orm prisma

-comando para interface banco de dados com prisma
## npx prisma studio 

--comando para sincronizar schema
## npx prisma migrate dev


## Requisites

- Docker;
- Node.js;

## Setup

- Clone the repository;
- Install dependencies (`npm install`);
- Setup PostgreSQL and Redis (`docker compose up -d`);
- Configure `.env.example` file (`cp .env.example .env`);
- Run application (`npm run dev`);
- Test it! (I personally recommend testing with [Hoppscotch](https://hoppscotch.io/)).
