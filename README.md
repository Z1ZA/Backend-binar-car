# Routers

- AUTH

1. Regis admin by superadmin (POST) = http://localhost:8000/api/auth/register-admin
2. Regis only member role (POST) = http://localhost:8000/api/auth/register
3. Login user (POST) = http://localhost:8000/api/auth/login
4. Check current user with token (GET) = http://localhost:8000/api/auth/me

- CARS (only access by admin or superadmin)

1. Get list cars (GET) = http://localhost:8000/api/cars
2. Get car by id (GET) = http://localhost:8000/api/cars/:id
3. Create car (POST) = http://localhost:8000/api/cars
4. Delete car by id (DELETE) = http://localhost:8000/api/cars/:id
5. Update car by id (PATCH) = http://localhost:8000/api/cars/:id

- USERS (only access by superadmin)

1. Get list users (GET) = http://localhost:8000/api/users
2. Get user by id (GET) = http://localhost:8000/api/users/:id
3. Create user (POST) = http://localhost:8000/api/users
4. Delete user by id (DELETE) = http://localhost:8000/api/users/:id
5. Update user by id (PATCH) = http://localhost:8000/api/users/:id

- SWAGGER
- run swagger-ui = http://localhost:8000/api-docs
