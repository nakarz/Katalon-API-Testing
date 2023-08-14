# Katalon API Testing
## _JSONPlaceholder_

Terdapat 2 _endpoints_, yaitu:
```
../albums
```
```
../todos
```
### Endpoint Albums
1. Melakukan method GET untuk seluruh Albums: 
```
https://jsonplaceholder.typicode.com/albums
```
2. Melakukan method GET untuk 10 Id pertama: 
 ```
https://jsonplaceholder.typicode.com/albums/1
https://jsonplaceholder.typicode.com/albums/2
..
https://jsonplaceholder.typicode.com/albums/10
```
3. Melakukan method POST untuk userId 1: 
```
https://jsonplaceholder.typicode.com/albums
{
    "userId": 1,
    "title": 'new album post for user1'
}
```
4. Melakukan method DELETE untuk Id 1:
```
https://jsonplaceholder.typicode.com/albums/1
```

### Endpoint ToDos
1. Melakukan method GET untuk seluruh ToDos: 
```
https://jsonplaceholder.typicode.com/todos
```
2. Melakukan method GET untuk 10 Id pertama: 
 ```
https://jsonplaceholder.typicode.com/todos/1
https://jsonplaceholder.typicode.com/todos/2
..
https://jsonplaceholder.typicode.com/todos/10
```
3. Melakukan method POST untuk userId 1: 
```
https://jsonplaceholder.typicode.com/todos
{
    "userId": 1,
    "title": 'new todo post for user1'
}
```
4. Melakukan method DELETE untuk Id 1:
```
https://jsonplaceholder.typicode.com/todos/1
```
