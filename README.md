
**GET /**

This endpoint is created for check web service functionality.

**Sample Request**

GET <WEB_SERVER_URL>/

**Sample Response**

```bash
Welcome to Postman Phase-2 Task!
```

---

**POST /trainee**

This endpoint is created for create new trainee with JSON body.

**Sample Request**

POST <WEB_SERVER_URL>/trainee

Body Type -> JSON

```json
{
    "name":"string",
    "surname":"string",
    "age":"number",
    "country":"string"
}
```

```json
{
    "name":"Cenk",
    "surname":"Ay",
    "age":24,
    "country":"Turkey"
}
```

**Sample Response**

```json
{
    "id": 1,
    "name": "Cenk",
    "surname": "Ay",
    "age": 24,
    "country": "Turkey"
}
```

---

**GET /trainee/{id}**



This endpoint is created for fetch Trainee information with ID

**Sample Request**

GET <WEB_SERVER_URL>/trainee/1

**Sample Response**

```json
{
    "id": 1,
    "name": "Cenk",
    "surname": "Ay",
    "age": 24,
    "country": "Turkey"
}
```

---

**PUT /trainee/{id}**

This endpoint is created for update Trainee information with ID

**Sample Request**

PUT <WEB_SERVER_URL>/trainee/1

Body -> JSON

```json
{
    "name":"Cem"
}
```

**Sample Response**

```bash
Trainee updated with ID: 1
```

---

**DELETE /trainee/{id}**

This endpoint is created for delete Trainee with ID

**Sample Request**

DELETE <WEB_SERVER_URL>/trainee/1

**Sample Response**

```bash
Trainee deleted with ID: 1
```



