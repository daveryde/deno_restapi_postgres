# Deno / REST API

Made with Deno. Stirred with third party modules denon and postgres. REST API with CRUD routes that access a postgres database.

## Installation

1. Install [Deno](https://deno.land/#installation) by choosing the option that meets your machine's OS.

2. Install [Postgres](https://www.postgresql.org/)

## Postgres Models

```sql
id: serial
name: text
description: text
price: numeric
```

# Windows Start Command

```bash
denon.cmd start
```

# Mac/Linux Start Command

```bash
denon start
```

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
