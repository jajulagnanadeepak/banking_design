# API Documentation

Base URL

```
http://localhost:5000
```

## Authentication

Register

POST /auth/register

```
{
 "firstName": "John",
 "lastName": "Doe",
 "email": "john@example.com",
 "password": "12345678"
}
```

Login

POST /auth/login

```
{
 "email": "john@example.com",
 "password": "12345678"
}
```

## Accounts

Create account

POST /accounts

Get accounts

GET /accounts

## Transactions

Transfer money

POST /transactions/transfer

Get transactions

GET /transactions

## Notifications

GET /notifications
