# Awesome Redis [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)

[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/awesomelists) &nbsp; [![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) &nbsp; [![Stripe](https://srv-cdn.himpfen.io/badges/stripe/stripe-flat.svg)](https://tinyurl.com/e8ymxdw3) &nbsp; [![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) &nbsp; [![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of tools, libraries, extensions, modules, GUI clients, and resources for Redis — the in-memory data store used for caching, vector search, pub/sub, streams, real-time apps, and AI workloads.

## Contents

- [Core](#core)
- [Clients](#clients)
- [Modules & Extensions](#modules--extensions)
- [Vector Search](#vector-search)
- [GUI Clients](#gui-clients)
- [CLI Tools](#cli-tools)
- [ORMs & Data Modeling](#orms--data-modeling)
- [Caching & Queues](#caching--queues)
- [Learning Resources](#learning-resources)
- [Related Awesome Lists](#related-awesome-lists)

## Core

- [Redis](https://redis.io/) – Official Redis documentation and downloads.
- [KeyDB](https://github.com/Snapchat/KeyDB) – Multithreaded, drop-in Redis alternative.
- [Valkey](https://github.com/valkey-io/valkey) – Open-source community fork of Redis.

## Clients

### JavaScript / TypeScript
- [redis](https://github.com/redis/node-redis) – Official Node.js client.
- [ioredis](https://github.com/luin/ioredis) – Robust Redis client with cluster and sentinel support.

### Python
- [redis-py](https://github.com/redis/redis-py) – Official Python client.
- [aioredis](https://github.com/aio-libs/aioredis-py) – Async Redis client for Python.

### Go
- [go-redis](https://github.com/redis/go-redis) – Official Go client.

### Rust
- [redis-rs](https://github.com/redis-rs/redis-rs) – Rust client for Redis.

### Java
- [Jedis](https://github.com/redis/jedis) – Java Redis client.
- [Lettuce](https://github.com/lettuce-io/lettuce-core) – Scalable Java Redis client with async support.

## Modules & Extensions

- [RedisJSON](https://github.com/RedisJSON/RedisJSON) – Native JSON ingestion, querying, and storage.
- [RedisSearch](https://github.com/RediSearch/RediSearch) – Full-text search, aggregations, hybrid search.
- [RedisGraph](https://github.com/RedisGraph/RedisGraph) – Graph database module for Redis (Cypher support).
- [RedisTimeSeries](https://github.com/RedisTimeSeries/RedisTimeSeries) – Time-series storage and queries.
- [RedisBloom](https://github.com/RedisBloom/RedisBloom) – Bloom filters, Cuckoo filters, Count-Min sketch.
- [ReJSON Commands](https://redis.io/docs/interact/json/) – JSONPath-based operations.

## Vector Search

- [Redis Vector Similarity Search](https://redis.io/docs/stack/search/reference/vectors/) – Native vector search for embeddings.
- [RedisVL](https://github.com/redis/redisvl) – Python client for building RAG and vector-enabled applications.
- [LangChain Redis Vectorstore](https://python.langchain.com/docs/integrations/vectorstores/redis/) – Redis-powered vector store for LangChain pipelines.
- [LlamaIndex Redis Vector Index](https://docs.llamaindex.ai/) – Vector retrieval using Redis.

## GUI Clients

- [RedisInsight](https://github.com/redis/redisinsight) – Official GUI for visualizing data, performance, and queries.
- [Medis](https://github.com/luin/medis) – Modern, open-source Redis GUI client.
- [Another Redis Desktop Manager](https://github.com/qishibo/AnotherRedisDesktopManager) – Fast, cross-platform desktop manager.

## CLI Tools

- [redis-cli](https://redis.io/docs/tools/redis-cli/) – Official command-line interface.
- [redis-commander](https://github.com/joeferner/redis-commander) – Web-based Redis management console.
- [redis-exporter](https://github.com/oliver006/redis_exporter) – Prometheus exporter for Redis stats.

## ORMs & Data Modeling

- [Redis OM (Node.js)](https://github.com/redis/redis-om-node) – ODM/ORM modeling layer for Redis.
- [Redis OM (Python)](https://github.com/redis/redis-om-python) – Model classes, indexes, and RedisJSON support.
- [Redis OM (TypeScript/TS + Redis Stack)](https://github.com/redis/redis-om-node) – Data modeling for RedisJSON and RediSearch.
- [EdgeDB Redis Integrations](https://github.com/edgedb/) – Hybrid storage + caching patterns.

## Caching & Queues

- [BullMQ](https://github.com/taskforcesh/bullmq) – Redis-backed job queue for Node.js.
- [Bull](https://github.com/OptimalBits/bull) – Long-standing Redis-based queue.
- [RQ (Redis Queue)](https://github.com/rq/rq) – Simple Python job queue.
- [Django Cache Backend (Redis)](https://github.com/jazzband/django-redis) – Django cache integration.
- [Flask-Caching + Redis](https://github.com/sh4nks/flask-caching) – Redis back-end for Flask caching.
- [Sidekiq](https://github.com/sidekiq/sidekiq) – Ruby background jobs using Redis.

## Learning Resources

- [Redis Documentation](https://redis.io/docs/) – Official docs.
- [Redis University](https://university.redis.com/) – Free, high-quality Redis training courses.
- [Redis Streams Guide](https://redis.io/docs/data-types/streams/) – Deep dive into Streams.
- [Redis Search Tutorials](https://redis.io/docs/stack/search/) – Full-text and vector search tutorials.
- [Redis Use Cases](https://redis.io/docs/latest/use/) – Caching, rate limiting, message queues, leaderboards, ML.

## Related Awesome Lists

- [Awesome Databases](https://github.com/awesomelistsio/awesome-db)
- [Awesome Vector Search](https://github.com/awesomelistsio/awesome-vector-search)
- [Awesome SQL](https://github.com/awesomelistsio/awesome-sql)
- [Awesome Self-Hosted](https://github.com/awesomelistsio/awesome-selfhosted)

## Contribute

Contributions are welcome!

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
