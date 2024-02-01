# Packages Install

SQLiteDB, Prisma, nextui, next-auth/authjs, Github OAuth

```bash
npm install @nextui-org/react framer-motion
npm install prisma
npm install --save-exact @auth/core@0.18.1 @auth/prisma-adapter@1.0.6 next-auth@5.0.0-beta.3
npm install zod
```

# database setup

```base
npx prisma init --datasource-provider sqlite
npx prisma migrate dev
```

# Auth setup

```
github oauth
client ID: e98734c639e220ababe1
client secrets: 2f5848883f1d2e632f05d231565cdb289ee995e9
```
