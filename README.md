# Docker for Swetrix Analytics API development

Stable versions of Docker Compose and services as of publication date.

## Environment variables

`.env`

```ini
DOCKER_VERSION=3.8
MYSQL_VERSION=8.0.30
REDIS_VERSION=7.0.4
CLICKHOUSE_VERSION=22.3.10.22

MYSQL_PORT=3306
REDIS_PORT=6379
CLICKHOUSE_PORT=8123
```

## Setting up

Connect to the `swetrix-api-mysql` and `swetrix-api-clickhouse` containers. Next, create the **analytics** database in each service.

## Usage

**MySQL**

- host - `127.0.0.1`
- port - `3306`
- user - `root`
- password - `(none)`
- database - `analytics`

**Redis**

- host - `127.0.0.1`
- port - `6379`
- user - `default`
- password - `(none)`
- database - `0`

**ClickHouse**

- host - `127.0.0.1`
- port - `8123`
- user - `default`
- password - `(none)`
- database - `analytics`