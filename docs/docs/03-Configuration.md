---
slug: /configuration
title: Configuration
---

## Environment variables

You can configure the database at runtime using various environment variables:

- `DATATUNES__SERVER__HOST` -
  host to listen for connections on
  (default: `0.0.0.0`)
- `DATATUNES__SERVER__PORTS__SQL` -
  port to listen for SQL connections on
  (default: `41000`)
- `DATATUNES__SERVER__PORTS__HTTP` -
  port to listen for HTTP connections on
  (default: `41001`)
- `DATATUNES__SERVER__PORTS__RPC` -
  port to listen for RPC connections on
  (default: `41002`)
- `DATATUNES__CREDENTIALS__ROOT__PASSWORD` -
  password for the root user
  (default: `password`)
- `DATATUNES__CREDENTIALS__USER__PASSWORD` -
  password for the main user
  (default: `password`)
