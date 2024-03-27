
#  Drinks-API

A Django REST Drinks API for Effortless Beverage Data Integration.
Performs all CRUDE operations to the Database.
- CREATE
- READ
- UPDATE
- DELETE
## Tech Stack

Python,
Django


## API Reference

#### Get all items

```http
  GET /drinks
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` |  Your API key |

#### Get item

```http
  GET drinks/<int:id>
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `int` | **Required**. Id of item to fetch |

#### POST

```http
  POST /drinks
```

| Body | Type     |     example           |
| :-------- | :------- | :------------------------- |
| ` ` | `json` |

```
 {
    "name": "Red Bull",
     "description": "Gives you wings."
} 
```
### UPDATE
```http
  PUT drinks/<int:id>
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `int` | **Required**. Id of item to update |

```
{
    "id": 8,
    "name": "Blue Red Bull",
    "description": "Guess the ingredients that makes you fly"
}
```
### DELETE
```http
  DELETE drinks/<int:id>
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `int` | **Required**. Id of item to delete |


#### admin
```http
admin/
```



## Contributing

Contributions are always welcome!


Please adhere to this project's `code of conduct`.


## Usage/Examples

```javascript
You can test the API with #postman for different endpoints.

Develop a front end that consumes the API

```


## Lessons Learnt

- Understanding Django and Django REST Framework: It is crucial to have a solid grasp of Django and the Django REST Framework before embarking on API development. This includes familiarity with Django's structure, features, and how the REST framework extends Django's capabilities
- Efficient API Design: Learning how to design APIs efficiently is key. This involves structuring endpoints, handling data serialization, and ensuring proper authentication and permissions are in place
- Serialization and Data Handling: Mastering serialization in Django REST Framework is essential for transforming complex data types into native Python data types that can be easily rendered into JSON, XML, or other content types.
- Testing and Debugging: Testing the API thoroughly during development is crucial. Tools like curl can be used to test API endpoints, ensuring they function as intended. Debugging processes are also vital for identifying and resolving issues effectively.
- Continuous Learning and Improvement: Staying updated with the latest features and best practices in Django REST API development is essential for continuous improvement and staying competitive in the field.

