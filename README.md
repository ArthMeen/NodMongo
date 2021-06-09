# NodeJs-ExpressJs-CRUD-operations
A Restful API with Node.js and MongoDB

## Installation

Use the package manager npm for installation.

```bash
npm install body-parser
npm install express
npm install mongodb
npm install mongoose
npm install validator
```

## Usage

```nodejs
localhost:3000/products/create with keys.
new CRUD operations will be added .
```

## Getting Started

1.  **Clone** this repository.
2.  **CD into the folder** where you cloned the repository.
3.  download all dependencies listed under Installation.
4.  After all dependencies finish downloading without errors, type `node app.js` to start the server.

### Create API Endpoints

| Method | Endpoint              | Description                                                                         |
| ------ | --------------------- | ------------------------------------------------------------------------------------|
| POST   | /products/create      | Creates a product using the information sent inside the `request body`.                |
| GET    | /products/get         | Returns an array of all the objects contained in the database.                 |
| PUT    | /products/:id/update  | Updates the product with the specified id using data from the `request body`.          |
| DELETE | /products/:id/delete  | Removes the product with the specified id and returns the deleted product.                |


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

