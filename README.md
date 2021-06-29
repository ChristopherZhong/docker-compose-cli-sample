# docker-compose-cli-sample

This sample project higlights an issue where the `#` character is treated differently in `docker-compose` versus `docker compose`

Using `docker-compose up` inspect the container and the `POSTGRES_PASSWORD` is `abc#123`.
But using `docker compose up`, the `POSTGRES_PASSWORD` is `abc`.
