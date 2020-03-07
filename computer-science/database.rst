General
=======
- Column-oriented DBMS
  https://en.wikipedia.org/wiki/Column-oriented_DBMS

RDBMS
=====
SQL in general
--------------
- JOIN (SQL)
  https://en.wikipedia.org/wiki/Join_(SQL)

- HAVING (SQL)
  https://en.wikipedia.org/wiki/Having_(SQL)

PostgreSQL
----------
- PostgreSQL Documentation (在读)

NoSQL
=====
general
-------
- NoSQL wiki
  https://en.wikipedia.org/wiki/NoSQL

- NoSQL databases
  http://nosql-database.org/

MongoDB
-------
- Getting Started with MongoDB: Mongo Shell

- Getting Started with MongoDB: Python Driver

- MongoDB manual
  https://docs.mongodb.com/manual/

  * indexes
    https://docs.mongodb.com/manual/indexes/

    - Single Field Indexes
      https://docs.mongodb.com/manual/core/index-single/

    - Compound Indexes
      https://docs.mongodb.com/manual/core/index-compound/

    - Index Build Operations
      https://docs.mongodb.com/manual/core/index-creation/

    - Index Properties

      * Unique Indexes
        https://docs.mongodb.com/manual/core/index-unique/

    - Indexing Strategies

      * Use Indexes to Sort Query Results
        https://docs.mongodb.com/manual/tutorial/sort-results-with-indexes/

  * MongoDB CRUD Operations

    - MongoDB CRUD Concepts

      * Query Optimization

        - Explain Results
          https://docs.mongodb.com/manual/reference/explain-results/

  * mongo shell methods

    - collection methods

      * ``replaceOne()``
        https://docs.mongodb.com/manual/reference/method/db.collection.replaceOne/

    - cursor methods

      * ``explain()``
        https://docs.mongodb.com/manual/reference/method/cursor.explain/

- PyMongo documentation

  * Datetimes and Timezones
    http://api.mongodb.com/python/current/examples/datetimes.html

Cache
=====

Memcached
---------

- wikipedia
  https://en.wikipedia.org/wiki/Memcached

- Memcached overview
  https://memcached.org/about

- Getting Started

  * Install
    https://github.com/memcached/memcached/wiki/Install

  * Tutorial
    https://github.com/memcached/memcached/wiki/TutorialCachingStory

Redis
-----

- wiki
  https://en.wikipedia.org/wiki/Redis

- homepage
  https://redis.io/

- Introduction to Redis
  https://redis.io/topics/introduction

- Download
  https://redis.io/download

- Tutorials

  * try redis
    http://try.redis.io/

  * Introduction to Redis data types
    https://redis.io/topics/data-types-intro

- Programming with Redis

  * Pub/Sub
    https://redis.io/topics/pubsub

  * Using pipelining to speedup Redis queries
    https://redis.io/topics/pipelining

  * Transactions
    https://redis.io/topics/transactions

  * The full list of commands

    - KEYS
      https://redis.io/commands/keys

    - SCAN
      https://redis.io/commands/scan

    - SUBSCRIBE
      https://redis.io/commands/subscribe

    - UNSUBSCRIBE
      https://redis.io/commands/unsubscribe

    - PSUBSCRIBE
      https://redis.io/commands/psubscribe

    - PUNSUBSCRIBE
      https://redis.io/commands/punsubscribe

    - PUBLISH
      https://redis.io/commands/publish

    - PUBSUB
      https://redis.io/commands/pubsub

    - SELECT
      https://redis.io/commands/select

    - WATCH
      https://redis.io/commands/watch

    - UNWATCH
      https://redis.io/commands/unwatch

    - MULTI
      https://redis.io/commands/multi

    - EXEC
      https://redis.io/commands/exec

    - DISCARD
      https://redis.io/commands/discard

    - GET
      https://redis.io/commands/get

    - SET
      https://redis.io/commands/set

    - INCR
      https://redis.io/commands/incr

    - GETSET
      https://redis.io/commands/getset

    - INCRBY
      https://redis.io/commands/incrby

    - INCRBYFLOAT
      https://redis.io/commands/INCRBYFLOAT

    - DECR
      https://redis.io/commands/decr

    - DECRBY
      https://redis.io/commands/decrby

    - MGET
      https://redis.io/commands/mget

    - MSET
      https://redis.io/commands/mset

    - EXISTS
      https://redis.io/commands/exists

    - DEL
      https://redis.io/commands/del

    - TYPE
      https://redis.io/commands/type

    - EXPIRE
      https://redis.io/commands/expire

    - PERSIST
      https://redis.io/commands/persist

    - TTL
      https://redis.io/commands/ttl

    - PTTL
      https://redis.io/commands/pttl

    - LPUSH
      https://redis.io/commands/lpush

    - RPUSH
      https://redis.io/commands/rpush

    - LRANGE
      https://redis.io/commands/lrange

    - LPOP
      https://redis.io/commands/lpop

    - RPOP
      https://redis.io/commands/rpop

    - LTRIM
      https://redis.io/commands/ltrim

    - BLPOP
      https://redis.io/commands/blpop

    - BRPOP
      https://redis.io/commands/brpop

    - RPOPLPUSH
      https://redis.io/commands/rpoplpush

    - BRPOPLPUSH
      https://redis.io/commands/brpoplpush

    - LREM
      https://redis.io/commands/LREM

    - HSET
      https://redis.io/commands/hset

    - HGET
      https://redis.io/commands/hget

    - HMSET
      https://redis.io/commands/hmset

    - HMGET
      https://redis.io/commands/hmget

    - HGETALL
      https://redis.io/commands/hgetall

    - HKEYS
      https://redis.io/commands/hkeys

    - HVALS
      https://redis.io/commands/hvals

    - HEXISTS
      https://redis.io/commands/hexists

    - HDEL
      https://redis.io/commands/hdel

    - HLEN
      https://redis.io/commands/hlen

    - HINCRBY
      https://redis.io/commands/hincrby

    - SADD
      https://redis.io/commands/sadd

    - SREM
      https://redis.io/commands/srem

    - SCARD
      https://redis.io/commands/scard

    - SMEMBERS
      https://redis.io/commands/smembers

    - SISMEMBER
      https://redis.io/commands/sismember

    - SINTER
      https://redis.io/commands/sinter

    - SINTERSTORE
      https://redis.io/commands/sinterstore

    - SUNION
      https://redis.io/commands/sunion

    - SUNIONSTORE
      https://redis.io/commands/sunionstore

    - SPOP
      https://redis.io/commands/spop

    - SRANDMEMBER
      https://redis.io/commands/srandmember

    - SDIFF
      https://redis.io/commands/sdiff

    - SDIFFSTORE
      https://redis.io/commands/sdiffstore

    - ZADD
      https://redis.io/commands/zadd

    - ZREM
      https://redis.io/commands/zrem

    - ZREMRANGEBYSCORE
      https://redis.io/commands/zremrangebyscore

    - ZREMRANGEBYLEX
      https://redis.io/commands/zremrangebylex

    - ZREMRANGEBYRANK
      https://redis.io/commands/zremrangebyrank

    - ZINCRBY
      https://redis.io/commands/zincrby

    - ZUNIONSTORE
      https://redis.io/commands/zunionstore

    - ZINTERSTORE
      https://redis.io/commands/zinterstore

    - ZSCORE
      https://redis.io/commands/zscore

    - ZLEXCOUNT
      https://redis.io/commands/zlexcount

    - ZRANGE
      https://redis.io/commands/zrange

    - ZREVRANGE
      https://redis.io/commands/zrevrange

    - ZRANGEBYSCORE
      https://redis.io/commands/zrangebyscore

    - ZREVRANGEBYSCORE
      https://redis.io/commands/zrevrangebyscore

    - ZRANGEBYLEX
      https://redis.io/commands/zrangebylex

    - ZREVRANGEBYLEX
      https://redis.io/commands/zrevrangebylex

    - ZPOPMIN
      https://redis.io/commands/zpopmin

    - ZPOPMAX
      https://redis.io/commands/zpopmax

    - BZPOPMIN
      https://redis.io/commands/bzpopmin

    - BZPOPMAX
      https://redis.io/commands/bzpopmax

    - ZRANK
      https://redis.io/commands/zremrangebylex

    - ZREVRANK
      https://redis.io/commands/zrevrank

    - ZCOUNT
      https://redis.io/commands/zcount

    - ZSCAN
      https://redis.io/commands/zscan

    - SETBIT
      https://redis.io/commands/setbit

    - GETBIT
      https://redis.io/commands/getbit

    - BICOUNT
      https://redis.io/commands/bitcount
   
    - BITOP
      https://redis.io/commands/bitop

    - BITPOS
      https://redis.io/commands/bitpos

    - PFADD
      https://redis.io/commands/pfadd

    - PFCOUNT
      https://redis.io/commands/pfcount

- Administration

  * redis-cli, the Redis command line interface
    https://redis.io/topics/rediscli

Search Engine
=============

Overview
--------
- Search Engine wiki
  https://en.wikipedia.org/wiki/Search_engine_(computing)

- Solr or Elasticsearch–That Is the Question
  https://www.datanami.com/2015/01/22/solr-elasticsearch-question/

Lucene
------
- Apache Lucene wiki
  https://en.wikipedia.org/wiki/Apache_Lucene

Elasticsearch
-------------
- Elasticsearch wiki
  https://en.wikipedia.org/wiki/Elasticsearch

- Elasticsearch: The Definitive Guide (在读)

- Elasticsearch Reference (在读)
  https://www.elastic.co/guide/en/elasticsearch/reference/current/index.html

Google
------
- Google Advanced Search Operators: The Ultimate List (40+ Advanced Operators)
  https://www.spyfu.com/blog/google-search-operators/

- Refine web searches
  https://support.google.com/websearch/answer/2466433?visit_id=637002234560518368-2298607146&p=adv_operators&hl=en&rd=1

- Google Search Operators
  https://moz.com/learn/seo/search-operators

- Mastering Google Search Operators in 67 Easy Steps
  https://moz.com/blog/mastering-google-search-operators-in-67-steps

- Google guide
  http://www.googleguide.com/

  * Entering a Query
    http://www.googleguide.com/entering_queries.html

  * Going Directly to the First Result
    http://www.googleguide.com/first_result.html

  * Selecting Search Terms
    http://www.googleguide.com/select_terms.html

  * Interpreting Your Query
    http://www.googleguide.com/interpreting_queries.html

  * Crafting Your Query by using Special Characters
    http://www.googleguide.com/crafting_queries.html

    - Quoted Phrases
      http://www.googleguide.com/quoted_phrases.html

    - The - operator
      http://www.googleguide.com/minus_operator.html

    - The OR and | Operators
      http://www.googleguide.com/or_operator.html

    - The .. Operator
      http://www.googleguide.com/number_range.html

    - The * Operator
      http://www.googleguide.com/wildcard_operator.html

  * Using search operators
    http://www.googleguide.com/using_advanced_operators.html

  * Favorite Features
    http://www.googleguide.com/category/favorite-features/
