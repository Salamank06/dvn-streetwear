# DVN · Tienda de streetwear

**Sitio en producción:** https://dvnshop.vercel.app

Tienda online de ropa streetwear. Todo corre en Vercel: el frontend y la API.

> El código es privado por acuerdo con el cliente. Este repositorio es un caso de estudio.

## Arquitectura
```
Navegador ──► Vercel
              ├── frontend (React + Vite + Tailwind)
              └── funciones serverless ──► Neon (Postgres)
                                       ◄── Bold (webhook de pagos)
```
Frontend y API comparten dominio, así que no hay CORS ni servidor aparte.

## Stack
React · Vite · Tailwind CSS · Vercel Functions · Neon (PostgreSQL) · Bold (pagos)

## Mi rol
Frontend, API, base de datos, integración de pagos y despliegue.
