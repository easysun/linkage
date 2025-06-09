# linkage
=======
A platform for recording family connections.

## Getting Started

These instructions will help you run the GraphQL server locally.

### Prerequisites
- Go 1.18+
- PostgreSQL (for future database integration)

### Install dependencies & generate code
```bash
go mod tidy
go generate ./graph/resolver
```

### Run the server
```bash
go run cmd/server/main.go
```

The service will start on port 8080 by default and expose a GraphQL playground at http://localhost:8080/.
