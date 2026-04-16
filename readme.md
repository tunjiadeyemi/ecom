start up server command: `go run cmd/\*.go`

to create a migration file: `goose -s create create_orders sql`

to apply migration file (changes) to the db: `goose up`

generate golang sql: `sqlc generate`
