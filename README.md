# SCIO LMS Backend

API REST para la plataforma e-learning SCIO LMS.

## Stack
- Node.js 22.x + Express
- MariaDB 10.11 (mysql2/promise)
- JWT Authentication (bcryptjs)
- Phusion Passenger (cPanel deploy)

## Estructura
```
app.js                  # Entry point (Passenger)
src/
  config/db.js          # DB pool
  middleware/           # auth, errorHandler, validate
  models/               # SQL queries por entidad
  controllers/          # Lógica de negocio
  routes/               # Definición de rutas
database/
  schema.sql            # Esquema completo
public/                 # React build (copiar aquí)
uploads/                # Archivos subidos
tmp/restart.txt         # Passenger restart
```

## Setup local
```bash
cp .env.example .env
# Editar .env con tus credenciales
npm install
npm run dev
```

## Deploy en cPanel
1. Comprimir proyecto SIN `node_modules/` ni `.env`
2. Subir ZIP via File Manager
3. "Run NPM Install" desde cPanel Node.js App
4. Configurar variables de entorno en cPanel UI
5. Copiar `frontend/dist/` → `public/`
6. Restart app desde cPanel

## API
- Docs: Ver `src/routes/` para todos los endpoints
- Auth: Bearer token en header `Authorization`
