RDBMS
=====
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

    - SQL statement syntax

      * database administration statements

        - Account Management Statements
          https://dev.mysql.com/doc/refman/8.0/en/account-management-sql.html

          * CREATE USER Syntax
            https://dev.mysql.com/doc/refman/8.0/en/create-user.html

        - SHOW Syntax

          * SHOW VARIABLES syntax
            https://dev.mysql.com/doc/refman/8.0/en/show-variables.html

          * SHOW SLAVE HOSTS Syntax
            https://dev.mysql.com/doc/refman/8.0/en/show-slave-hosts.html

          * SHOW SLAVE STATUS Syntax
            https://dev.mysql.com/doc/refman/8.0/en/show-slave-status.html

          * SHOW CREATE USER Syntax
            https://dev.mysql.com/doc/refman/8.0/en/show-create-user.html

          * SHOW GRANTS Syntax
            https://dev.mysql.com/doc/refman/8.0/en/show-grants.html

    - Security

      * MySQL User Account Management
        https://dev.mysql.com/doc/refman/8.0/en/user-account-management.html

        - User Names and Passwords
          https://dev.mysql.com/doc/refman/8.0/en/user-names.html

        - Adding User Accounts
          https://dev.mysql.com/doc/refman/8.0/en/adding-users.html

        - Remove User Accounts
          https://dev.mysql.com/doc/refman/8.0/en/removing-users.html

        - Reserved User Accounts
          https://dev.mysql.com/doc/refman/8.0/en/reserved-users.html

    - Server Administration

      * Server Logs

        - Binary Log
          https://dev.mysql.com/doc/refman/5.7/en/binary-log.html

          * binary logging formats
            https://dev.mysql.com/doc/refman/5.7/en/binary-log-formats.html

          * Setting The Binary Log Format
            https://dev.mysql.com/doc/refman/5.7/en/binary-log-setting.html

    - Replication
      https://dev.mysql.com/doc/refman/5.7/en/replication.html

      * Configuring replication
        https://dev.mysql.com/doc/refman/5.7/en/replication-configuration.html

        - Binary Log File Position Based Replication Configuration Overview
          https://dev.mysql.com/doc/refman/5.7/en/binlog-replication-configuration-overview.html

        - Setting Up Binary Log File Position Based Replication
          https://dev.mysql.com/doc/refman/5.7/en/replication-howto.html

          * Setting the Replication Master Configuration
            https://dev.mysql.com/doc/refman/5.7/en/replication-howto-masterbaseconfig.html
          * Creating a User for Replication
            https://dev.mysql.com/doc/refman/5.7/en/replication-howto-repuser.html

          * Obtaining the Replication Master Binary Log Coordinates
            https://dev.mysql.com/doc/refman/5.7/en/replication-howto-masterstatus.html

          * Choosing a Method for Data Snapshots
            https://dev.mysql.com/doc/refman/5.7/en/replication-snapshot-method.html

          * Setting Up Replication Slaves
            https://dev.mysql.com/doc/refman/5.7/en/replication-setup-slaves.html

        - Common Replication Administration Tasks
          https://dev.mysql.com/doc/refman/5.7/en/replication-administration.html

          * Checking Replication Status
            https://dev.mysql.com/doc/refman/5.7/en/replication-administration-status.html

      * Replication Implementation
        https://dev.mysql.com/doc/refman/5.7/en/replication-implementation.html

        - Replication formats
          https://dev.mysql.com/doc/refman/5.7/en/replication-formats.html

          * Advantages and Disadvantages of Statement-Based and Row-Based Replication
            https://dev.mysql.com/doc/refman/5.7/en/replication-sbr-rbr.html

        - Replication Implementation Details
          https://dev.mysql.com/doc/refman/5.7/en/replication-implementation-details.html

        - Replication Relay and Status Logs
          https://dev.mysql.com/doc/refman/5.7/en/slave-logs.html

          * The Slave Relay Log
            https://dev.mysql.com/doc/refman/5.7/en/slave-logs-relaylog.html

          * Slave Status Logs
            https://dev.mysql.com/doc/refman/5.7/en/slave-logs-status.html

    - MySQL Performance Schema

      * Performance Schema Table Descriptions

        - Performance Schema Replication Tables
          https://dev.mysql.com/doc/refman/8.0/en/performance-schema-replication-tables.html

          * The replication_connection_configuration Table
            https://dev.mysql.com/doc/refman/8.0/en/replication-connection-configuration-table.html

          * The replication_connection_status Table
            https://dev.mysql.com/doc/refman/8.0/en/replication-connection-status-table.html

          * The replication_applier_status Table
            https://dev.mysql.com/doc/refman/8.0/en/replication-applier-status-table.html

          * The replication_applier_global_filters Table
            https://dev.mysql.com/doc/refman/8.0/en/replication-applier-global-filters-table.html

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

- Percona tools

  * Percona XtraBackup Documentation
    https://www.percona.com/doc/percona-xtrabackup/LATEST/index.html

    - About Percona XtraBackup
      https://www.percona.com/doc/percona-xtrabackup/LATEST/intro.html

    - Installation
      https://www.percona.com/doc/percona-xtrabackup/LATEST/installation.html

      * Installing Percona XtraBackup on Debian and Ubuntu
        https://www.percona.com/doc/percona-xtrabackup/LATEST/installation/apt_repo.html

    - Prerequisites

      * Connection and Privileges Needed
        https://www.percona.com/doc/percona-xtrabackup/LATEST/using_xtrabackup/privileges.html

    - backups

      * full backup
        https://www.percona.com/doc/percona-xtrabackup/LATEST/backup_scenarios/full_backup.html

      * Accelerating the backup process
        https://www.percona.com/doc/percona-xtrabackup/LATEST/innobackupex/parallel_copy_ibk.html

      * Performing MySQL Hot Backups with Percona XtraBackup and Google Cloud Storage
        https://cloud.google.com/solutions/mysql-hot-backups

    - replication

      * working with binlogs
        https://www.percona.com/doc/percona-xtrabackup/LATEST/xtrabackup_bin/working_with_binary_logs.html

      * How to setup a slave for replication in 6 simple steps with Percona XtraBackup
        https://www.percona.com/doc/percona-xtrabackup/LATEST/howtos/setting_up_replication.html

    - The xtrabackup Option Reference
      https://www.percona.com/doc/percona-xtrabackup/LATEST/xtrabackup_bin/xbk_option_reference.html

  * xbstream binary
    https://www.percona.com/doc/percona-xtrabackup/LATEST/xbstream/xbstream.html

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

    - ``JOIN``

    - ``UNION``

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

    - INNER JOIN ON

    - LEFT JOIN ON

    - source

    - MAX()

    - MIN()

    - LIMIT

    - zerofill

    - LAST_INSERT_ID()

    - REFERENCES

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
