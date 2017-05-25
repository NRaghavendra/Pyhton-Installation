# Configuring Django to use PostgreSQL

## Introdution

**PostgreSQl**, often simply **Postgres**, is an object-relational database (ORDBMS) – i.e. an RDBMS, with additional (optional use) "object" features – with an emphasis on extensibility and standards compliance. As a database server, its primary functions are to store data securely and return that data in response to requests from other software applications.

PostgreSQL boasts sophisticated features such as Multi-Version Concurrency Control (MVCC), point in time recovery, tablespaces, asynchronous replication, nested transactions (savepoints), online/hot backups, a sophisticated query planner/optimizer, and write ahead logging for fault tolerance.

Django is a flexible framework for quickly creating Python applications. By default, Django applications are configured to store data into a lightweight SQLite database file. While this works well under some loads, a more traditional DBMS can improve performance in production.

In this tutorial, we'll demonstrate how to install and configure MySQL or MariaDB to use with your Django applications. We will install the necessary software, create database credentials for our application, and then start and configure a new Django project to use this backend.

## prerequisites

A Ubuntu machine(requires **Sudo** privileges for user) with Internet.

