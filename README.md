# Salud 44 – Backend

API REST para un sistema de gestión de pacientes y doctores, desarrollada durante la simulación profesional de NoCountry (2024) en un equipo remoto.

## Tecnologías

- NestJS 11 (Node.js + TypeScript)
- PostgreSQL con Prisma ORM
- Autenticación con JWT (Passport) y contraseñas cifradas con bcrypt
- Validación de datos con class-validator y class-transformer
- Documentación de la API con Swagger
- Pruebas con Jest y Supertest

## Funcionalidades

- [ESCRIBE AQUÍ: por ejemplo, registro e inicio de sesión de usuarios]
- [ESCRIBE AQUÍ: por ejemplo, gestión de pacientes]
- [ESCRIBE AQUÍ: por ejemplo, gestión de doctores]

## Mi participación

- [ESCRIBE AQUÍ: qué módulos o endpoints desarrollaste tú]
- [ESCRIBE AQUÍ: qué resolviste: autenticación, base de datos, pruebas, documentación...]
- Trabajo en equipo con Git/GitHub: ramas, revisión de código y resolución de conflictos de integración.

## Requisitos

- Node.js 20 o superior
- PostgreSQL
- npm

## Instalación

```bash
git clone https://github.com/Victor-RivasDev/Salud---44-No.Country__Back.git
cd Salud---44-No.Country__Back
npm install
```

## Variables de entorno

Crea un archivo `.env` en la raíz del proyecto, tomando como base `.env.example`:

```
DATABASE_URL=postgresql://usuario:contraseña@localhost:5432/nombre_bd
JWT_SECRET=cambia_esto
```

## Base de datos

```bash
npx prisma migrate dev
npm run seed
```

El comando `seed` carga datos de ejemplo.

## Ejecutar el proyecto

```bash
# desarrollo
npm run start:dev

# producción
npm run build
npm run start:prod
```

## Pruebas

```bash
npm run test       # unitarias
npm run test:e2e   # extremo a extremo
npm run test:cov   # cobertura
```

## Documentación de la API

Con el proyecto en marcha, la documentación de Swagger está disponible en `http://localhost:3000/api`.

## Frontend

El cliente de este proyecto está en: https://github.com/Victor-RivasDev/Salud---44-No.Country__Front

## Autor

Victor J. Rivas Z. – [LinkedIn](https://www.linkedin.com/in/victor-josue-rivas-zambrano-809161164) | [Portafolio](https://portafoliovj.netlify.app)
