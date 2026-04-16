# Card Management API

This project is a simple Node.js REST API for managing cards. It follows a basic MVC structure with controllers, models, routes, and services.

## Project Structure

```
index.js                # Entry point of the application
package.json            # Project metadata and dependencies
controllers/            # Route handler logic
  card.controller.js
models/                 # Database models
  card.model.js
routes/                 # API route definitions
  card.routes.js
services/               # Business logic
  card.service.js
```

## Getting Started

### Prerequisites
- Node.js (v14 or higher recommended)
- pnpm (or npm/yarn)

### Installation
1. Clone the repository or download the source code.
2. Install dependencies:
   ```sh
   pnpm install
   # or
   npm install
   ```

### Running the Application
Start the server with:
```sh
node index.js
```

The server will start on the configured port (default: 3000).

## API Endpoints

- `GET /cards` - Get all cards
- `GET /cards/:id` - Get a card by ID
- `POST /cards` - Create a new card
- `PUT /cards/:id` - Update a card by ID
- `DELETE /cards/:id` - Delete a card by ID

## License

This project is licensed under the MIT License.
