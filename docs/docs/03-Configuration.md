---
slug: /config
title: Configuration
---

## Environment variables

You can configure the database at runtime using various environment variables:

- `GRAPHITE__SERVER__HOST` -
  host to listen for connections on
  (default: `0.0.0.0`)
- `GRAPHITE__SERVER__PORTS__SQL` -
  port to listen for SQL connections on
  (default: `10220`)
- `GRAPHITE__SERVER__PORTS__HTTP` -
  port to listen for HTTP connections on
  (default: `10221`)
- `GRAPHITE__SERVER__PORTS__RPC` -
  port to listen for RPC connections on
  (default: `10222`)
- `GRAPHITE__CREDENTIALS__ROOT__PASSWORD` -
  password for the root user
  (default: `password`)
- `GRAPHITE__CREDENTIALS__USER__PASSWORD` -
  password for the main user
  (default: `password`)
