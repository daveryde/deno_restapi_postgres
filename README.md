# Deno / REST API

Made with Deno. Stirred with third party modules denon and postgres. REST API with CRUD routes that access hard coded json data to mimic accessing a database.

## Installation

1. Install [Deno](https://deno.land/#installation) by choosing the option that meets your machine's OS.

2. Install [Postgres](https://www.postgresql.org/)

3. Create Database Models

```sql
id: serial
name: text
description: text
price: numeric
```

# Windows

```bash
denon.cmd start
```

# Mac/Linux

```bash
denon start
```

# Postgres

## Usage

GET Routes
* http://localhost:5000/api/v1/items/
* http://localhost:5000/api/v1/items/1

PUT Routes
* http://localhost:5000/api/v1/items/1

DELETE Routes
* http://localhost:5000/api/v1/items/1

POST Routes
* http://localhost:5000/api/v1/items

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
