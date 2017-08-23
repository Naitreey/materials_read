RDBMS
=====
SQL language
------------

PostgreSQL
----------
- PostgreSQL Documentation (在读)

MySQL
-----
- MySQL documentation
  https://dev.mysql.com/doc/

  * Getting Started with MySQL
    https://dev.mysql.com/doc/mysql-getting-started/en/

  * MySQL Reference Manual

    - Tutorial
      https://dev.mysql.com/doc/refman/5.7/en/tutorial.html

- Python driver choice

  * python mysql wiki
    https://wiki.python.org/moin/MySQL

  * django mysql driver
    https://docs.djangoproject.com/en/1.11/ref/databases/#mysql-db-api-drivers

  * openstack PyMySQL evaluation
    https://wiki.openstack.org/wiki/PyMySQL_evaluation

  * stackoverflow answer for comparison of MySQLdb, PyMySQL, mysqlclient,
    MySQL connector/python
    https://stackoverflow.com/questions/43102442/whats-the-difference-between-mysqldb-mysqlclient-and-mysql-connector-python

- MySQL 语句自动化审核系统: inception

  * source code
    https://github.com/mysql-inception/inception

  * 使用规范及说明文档
    http://mysql-inception.github.io/inception-document/

  * archer 基于 inception 的自动化 SQL 操作平台
    https://github.com/jly8866/archer

- Coursera: Managing Big Data with MySQL (by Duke University)
  https://www.coursera.org/learn/analytics-mysql/

- mycli: A Terminal Client for MySQL with AutoCompletion and Syntax Highlighting
  https://github.com/dbcli/mycli

  * docs
    http://www.mycli.net/docs

- MySQL SQL language

  * DDL

    - ``CREATE DATABASE``

    - ``CREATE TABLE``

    - ``ALTER TABLE``

  * DML

    - ``LOAD DATA INFILE``

    - ``INSERT``

    - ``SELECT``

    - ``DELETE``

    - ``UPDATE``

  * Administration statements

    - ``CREATE USER``

    - ``GRANT``

    - ``SHOW``

  * Utility statements

    - ``QUIT``

    - ``USE``

    - ``DESCRIBE``

  * Logical operatos

   - AND

   - OR

   - IS NULL

   - IS NOT NULL

   - LIKE

   - NOT LIKE

   - RLIKE

   - NOT RLIKE

   - REGEXP

   - NOT REGEXP

  * misc

    - VERSION()

    - CURRENT_DATE

    - NOW()

    - DATABASE()

    - DISTINCT

    - ORDER BY

    - WHERE

    - BINARY

    - TIMESTAMPDIFF()

    - YEAR()

    - MONTH()

    - DAYOFMONTH()

    - DATE_ADD()

    - CURDATE()

    - COUNT()

    - GROUP BY

    - INNER JOIN ... ON ...

- mysql client commands

  * ``\g``, ``\G``

  * ``\c``

NoSQL
=====

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

  *
