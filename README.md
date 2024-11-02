# Практическая задача 4.3.9

```
{
    "registration": {
        "type": "POST",
        "url": "https://blog.kata.academy/api/users",
        "request": {
            "user": {
                "username": "arttest",
                "email": "art-test@m.test",
                "password": "strinG"
            }
        },
        "response": {
            "user": {
                "username": "arttest",
                "email": "art-test@m.test",
                "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY2MzUzNTA2OGM4MjhkMWIwMDM5NjgzNyIsInVzZXJuYW1lIjoiYXJ0dGVzdCIsImV4cCI6MTcxOTk0NzAxNSwiaWF0IjoxNzE0NzYzMDE1fQ.s1GaWuVD4RcqDwzhc_ONWT44FYvBhvLgAkVO9EIbuB0"
            }
        }
    },
    "authentication": {
        "type": "POST",
        "url": "https://blog.kata.academy/api/users/login",
        "request": {
            "user": {
                "email": "art-test@m.test",
                "password": "strinG"
            }
        },
        "response": {
            "user": {
                "username": "arttest",
                "email": "art-test@m.test",
                "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY2MzUzNTA2OGM4MjhkMWIwMDM5NjgzNyIsInVzZXJuYW1lIjoiYXJ0dGVzdCIsImV4cCI6MTcxOTk0OTIwNSwiaWF0IjoxNzE0NzY1MjA1fQ._BytSIesPXuk0rFcnOwxgZ10tyh92YPZAHQ5FeEJ6GI"
            }
        }
    },
    "get current user": {
        "type": "GET",
        "url": "https://blog.kata.academy/api/user",
        "headers": {
            "Authorization": "Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY2MzUzNTA2OGM4MjhkMWIwMDM5NjgzNyIsInVzZXJuYW1lIjoiYXJ0dGVzdCIsImV4cCI6MTcxOTk0Nzc2MCwiaWF0IjoxNzE0NzYzNzYwfQ.60jxmb54VblIpGlXUFvoDf7nIXIVeHo0eODrrcMo0G8"
        },
        "response": {
            "user": {
                "username": "arttest",
                "email": "art-test@m.test",
                "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY2MzUzNTA2OGM4MjhkMWIwMDM5NjgzNyIsInVzZXJuYW1lIjoiYXJ0dGVzdCIsImV4cCI6MTcxOTk0Nzc2MCwiaWF0IjoxNzE0NzYzNzYwfQ.dqxnRJKh00jSYu6KeC2vsQVsJiYLtCd0JZ4JJWRdHu8"
            }
        }
    }
}
```