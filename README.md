# my_fullstack

Full-stack admin system for editing the content part of a website.

The project consists of two applications:

- an admin panel for managing content entries;
- a backend API that stores and serves this content.

This solution is designed for a closed/private system. Both the frontend and backend use JWT-based authorization with assumptions appropriate for an internal environment. If you want to use these services in a different context, especially as a public-facing system, you will need to redesign and configure authentication and authorization accordingly.

## Stack

Backend:
- NestJS
- TypeScript
- GraphQL / Apollo
- MongoDB / Mongoose
- JWT auth
- Docker

Frontend:
- React
- TypeScript
- Apollo Client
- Material UI
- GraphQL
- Docker
- Nginx

## Repositories

- Backend: https://github.com/kapustiansky/my_server
- Frontend: https://github.com/kapustiansky/my_admin