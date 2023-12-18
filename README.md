# FastApi Firebase Auth
Authentication api built using fastapi and firebase

## Documentation
To view api documentation click on [Documentation](http://127.0.0.1:8000/docs)


## Endpoints

### Register
Create user account to use application
```bash
curl -X POST http://127.0.0.1:8000/api/auth/register -H "Content-Type: application/json" -d '{"email": "your_email@example.com", "password": "your_password"}'
```

### Login
Login user with email and password returns jwt
```bash
curl -X POST http://127.0.0.1:8000/api/auth/login -H "Content-Type: application/json" -d '{"email": "your_email@example.com", "password": "your_password"}'
```

### Ping
Login user with email and password returns jwt
```bash
curl -X POST http://127.0.0.1:8000/api/auth/ping -H "Content-Type: application/json" -H "Authorization: your_access_token"
```

