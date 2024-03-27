
#  Drinks-API

A Django REST Drinks API Repository for Effortless Beverage Data Integration.
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

