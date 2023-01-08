# Headless SaaS API

This is a headless SaaS API that can be used to create a SaaS application.

It is built on top of [Next.js](https://nextjs.org/) API routes and uses [Prisma](https://www.prisma.io/) as the ORM.

## All API routes

### Authentication

- POST /api/auth/signup
- POST /api/auth/signin

### Teams

- POST /api/teams
- GET /api/teams
- GET /api/teams/:id
- DELETE /api/teams/:id
