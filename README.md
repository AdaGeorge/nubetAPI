# Nubet

real estate company


- Express
- PostgreSQL
- Sequelize ORM
- Autenticación con Tokens
- Bcrypt para hashear contraseñas
- Uso de Json Web Token

----

# .env
NODE_ENV = development

# Variables de entorno de mi base de datos
DB_HOST = localhost
DB_USER = postgres
DB_PASS = password
DB_NAME = example_db
DB_PORT = 5432
JWT_SECRET = word

-----------

# Modelos

- Users
- Roles
- Conversations
- Messages
- Notifications
- Properties
- Reservations
- Clients 
- Services


# Rutas

- Rutas de Login y register

 1. /api/v1/users
 2. /api/v1/users/me
 3. /api/v1/users/:id
 4. /api/v1/auth/register
 5. /api/v1/auth/login
 6. /api/v1/auth/recovery_password
 7. /api/v1/auth/verify_user