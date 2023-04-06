Работа с API 

https://blog.kata.academy/api

________________________________
Регистрация

Запрос:

{
  "user": {
    "username": "GlebTroyakov",
    "email": "glebtroyakov@gmail.com",
    "password": "1234qwer",
  }
}

Ответ:

{
    "user": {
        "username": "GlebTroyakov",
        "email": "glebtroyakov@gmail.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY0MmVjYmE0NjBjNjc1MWIwMGI3NGJhNCIsInVzZXJuYW1lIjoiZ2xlYnRyb3lha292IiwiZXhwIjoxNjg1OTcyMzg4LCJpYXQiOjE2ODA3ODgzODh9._oDPNf_eZL_bbHhO3ABLszfbm7FYVRbNrEsgq52Cyqw"
    }
}

________________________________
Вход 

Запрос:

{
  "user": {
    "email": "glebtroyakov@gmail.com",
    "password": "1234qwer"
  }
}


Ответ:

{
    "user": {
        "username": "glebtroyakov",
        "email": "glebtroyakov@gmail.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY0MmVjYmE0NjBjNjc1MWIwMGI3NGJhNCIsInVzZXJuYW1lIjoiZ2xlYnRyb3lha292IiwiZXhwIjoxNjg1OTc0MzU2LCJpYXQiOjE2ODA3OTAzNTZ9.Wb57F0IkB0Kolkdh85slULjmhWTXxPnDtr0oLmZSp_Y"
    }
}

________________________________
Получение пользователя

Запрос:

В Authorization вписал токен

Ответ:

{
    "user": {
        "username": "glebtroyakov",
        "email": "glebtroyakov@gmail.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjY0MmVjYmE0NjBjNjc1MWIwMGI3NGJhNCIsInVzZXJuYW1lIjoiZ2xlYnRyb3lha292IiwiZXhwIjoxNjg1OTc1OTI1LCJpYXQiOjE2ODA3OTE5MjV9.BeKYkUPk4W32xgN_Bg8MLN3sPz8nDFDAePdFgw-me2M"
    }
}
