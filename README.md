# node-typescript-api-setup

Steps
1. `npm install express cors dotenv helmet compression pino pino-pretty zod sequelize pg pg-hstore`

2. Directory structure
secure-api/
│── src/
│   ├── config/
│   │   ├── db.ts
│   │   ├── logger.ts
│   │   ├── env.ts
│   ├── middlewares/
│   │   ├── errorHandler.ts
│   │   ├── validation.ts
│   ├── routes/
│   │   ├── health.route.ts
│   ├── controllers/
│   │   ├── health.controller.ts
│   ├── models/
│   ├── app.ts
│   ├── server.ts
│── .env
│── .gitignore
│── tsconfig.json
│── package.json
│── README.md
