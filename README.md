#Blocitoff
A rake automated todo list

To seed:
```
rake db:schema:load
rake db:seed
```

Make an API call using curl:
```
curl -H "X-Api-Key: YOUR-KEY" http://localhost:3000/api/v1/lists.json
```
To create a list via the api with curl:
```
curl -H "X-Api-Key: TCwrsTTMp8C2H1vIHPNX4wtt" -d "list[title]=Test" http://localhost:3000/api/v1/lists
```
To delete one:
```
curl -H "X-Api-Key: TCwrsTTMp8C2H1vIHPNX4wtt" -X DELETE http://localhost:3000/api/v1/lists/[:id]
```