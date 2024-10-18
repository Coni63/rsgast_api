# Rsgast API

For learning purpose, create an API in Rust similar to Ergast API using Ergast Data (up to end of 2023).

## Development:

1. Start the database in docker

```sh
cd docker
docker compose up -d
```

2. Setup a `.env` file

```
SERVER_ADDR=127.0.0.1:8080
PG__USER=user
PG__PASSWORD=password
PG__HOST=localhost
PG__PORT=5432
PG__DBNAME=postgres
PG__POOL_MAX_SIZE=16
```

3. Start the app with a hot reload or production

```sh
cargo watch -x run  # hot reload
cargo run --release # release mod
```
