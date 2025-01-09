# User API

## Register User

Endpoint : POST /api/users/register

Request Body :

```json
{
  "username": "rahasia",
  "password": "rahasia",
  "name": "raka",
  "phone": 08772323222,
  "address": "jalan raya"
}
```

Response Body (Success) :

```json
{
  "message": "Berhasil membuat akun",
  "data": {
    "username": "rahasia",
    "name": "raka"
  }
}
```

Response Body (Failed) :

```json
{
  "errors": "Username sudah terdaftar",
}
```

## Login User

Endpoint : POST /api/users/login

## Get User

Endpoint : GET /api/users

## Update User

Endpoint : PUT /api/users

## Delete User

Endpoint : DELETE /api/users

## Logout User

Endpoint : POST /api/users/logout
