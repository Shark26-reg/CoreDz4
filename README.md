# CoreDz4
### request
```GRAPHQL
mutation login{
   login( request:{
     email: "admin@example.com"
     password: "Qwert!2345"
     role: ADMINISTRATOR
   }  
   )
}
```

### response
```GRAPHQL
{
  "data": {
    "login": "Status: 200 (OK); Body: \"eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJodHRwOi8vc2NoZW1hcy54bWxzb2FwLm9yZy93cy8yMDA1LzA1L2lkZW50aXR5L2NsYWltcy9lbWFpbGFkZHJlc3MiOiJhZG1pbkBleGFtcGxlLmNvbSIsImh0dHA6Ly9zY2hlbWFzLm1pY3Jvc29mdC5jb20vd3MvMjAwOC8wNi9pZGVudGl0eS9jbGFpbXMvcm9sZSI6IkFkbWluaXN0cmF0b3IiLCJleHAiOjE3MDc3NjkwMTIsImlzcyI6Imh0dHBzOi8vbG9jYWxob3N0OjcyMjQiLCJhdWQiOiJodHRwczovL2xvY2FsaG9zdDo3MjI0In0.RDBNikK62aXJ23Eyy0nEen2fBYCe2n1VJmOXZYBlLt4\""
  }
}
