# First Steps in GO!!!
- Small API made following the next tutorial on go.dev https://go.dev/doc/tutorial/web-service-gin

to use it, clone the repo and made the changes of your PATH
- to run the use the command:
```GO
go run .
```
- To consume use PostMan or the follow comand after running the API:
```GO
curl http://localhost:8080/albums
```
- and this one to use POST method:
```GO
curl http://localhost:8080/albums \
    --include --header \
    "Content-Type: application/json" \
    --request "POST" --data \
    '{"id": "4","title": "The Modern Sound of Betty Carter","artist": "Betty Carter","price": 49.99}'
```

--- 
# PREVIEW OF THE RESPONSES
![image](https://github.com/user-attachments/assets/601822bb-44f8-4312-80d2-53cb153c603f)

## Important
if you dont have gin after after clone the repo use you uncondicional habilities to resolve the problem because I dont know how to fix that XD
