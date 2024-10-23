# First Steps in GO!!!
- Small API made following the next tutorial on go.dev https://go.dev/doc/tutorial/web-service-gin

to use it, clone the repo and made the changes of your PATH
use the command:
```GO
go run .
```
to run the application and consume use PostMan or the follow comand:
```GO
curl http://localhost:8080/albums
```

---
You can use GET and POST method!!!
Before I mention the comand to consume the API that funtion to use GET method 
And this one:
```GO
curl http://localhost:8080/albums \
    --include --header \
    "Content-Type: application/json" \
    --request "POST" --data \
    '{"id": "4","title": "The Modern Sound of Betty Carter","artist": "Betty Carter","price": 49.99}'
```
to use POST method
