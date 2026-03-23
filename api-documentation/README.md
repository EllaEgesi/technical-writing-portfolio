# API Documentation Project

## Overview

This project demonstrates a simple example of API documentation.

API documentation explains how developers interact with a software service using endpoints, requests, and responses.

In this example, the API allows users to retrieve a list of users from the system.


## Authentication

All API requests require an API key.

Include the API key in the request header:

```bash
Authorization: Bearer YOUR_API_KEY
```
## Endpoint

### GET /users

Description

Returns a list of users from the system.

#### Example Request

```bash
curl https://api.example.com/users
```

#### Example Response

```json
{
  "users": [
    {
      "id": 1,
      "name": "Jane"
    },
    {
      "id": 2,
      "name": "Alex"
    }
  ]
}
