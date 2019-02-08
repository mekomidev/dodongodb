# Project roadmap

> The goal of the DodongoDB project is to provide an embedded-first document-oriented DB in Dart, inspired by MongoDB's API

## DodongoDB v0.1

### Features
  - In-memory store driver (no persistence)
  - Basic Future-based API
    - `create()`
    - `find()`
    - `findOne()`
    - `update()`
    - `remove()`
  - 

## DodongoDB v1.0
  - A more complete API
  - On-disk store driver (persistence)
    - BSON support
  - Performance improvements

## Further down...
  - Multiple DBs
  - User management
  - Client-server option
    - Server wrapper
    - Client driver
    - Secure connection (TLS)
  - Security
    - Authentication & authorization (user-based)
    - On-disk encryption
  - More store drivers...
    - S3?
    - Firebase?
    - *we're open to proposals, but we don't promise anything*
  - Reactive wrapper

## What is NOT planned (for now)

Below you will find a list of features our team is currently not taking into consideration while developing DodongoDB, *as of now*. This could be subject to change in the future, with enough backing from the community and if within our scope.

  - Aggregation pipeline
  - Replication, sharding, synchronization
  - Ports/wrappers in other languages/frameworks
