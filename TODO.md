# Lab 7

TODO: error message for when an author is not found
find the todos i left in the code

## Running it
Read the provided README: `SEG3502_Lab7_Starter/README.md`
This means the run intructions will be different than usually in the report.


## Swagger

New db is empty, add stuff through Swagger (localhost:8080/swagger-ui.html).

`POST /books`:

```json
{
  "title": "It's Not Easy Being Green",
  "category": "Biography",
  "isbn": "123-456",
  "cost": 25.45,
  "year": 2017,
  "description": "Kermit the Frog looks back on life in the swamp and running the Muppet Show"
}
```

`POST /books/{id}/authors` with the book id (not isbn) you got back:

```json
{
  "firstName": "Kermit",
  "lastName": "The Frog"
}
```
