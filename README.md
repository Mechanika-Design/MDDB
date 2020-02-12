MDDB Data Access Layer
======================

A PHP library that provides a portable, cross-platform, cross-database, lightweight, debuggable, replication-aware, migration-friendly, transaction capable, data access layer (DAL) for PHP 5.3 and later.

Features
--------

* Cross-platform - Runs under PHP 5.3 and later for all OSes that PHP supports.
* Cross-database capable - The same application code can generate two completely different queries for two different database products but achieve the same result.
* Lightweight - The base class one derived class instantiation plus an active database connection only uses an additional 300KB-570KB RAM (depending on the database).
* Debuggable - Easily see the output of each query, it's parameter values, query number, how long the query took, and total time for all queries for the current connection.
* Replication-aware - Automatically switches to a replication master when running change queries (INSERT, UPDATE, DELETE, etc.).
* Migration-friendly - The full versions of each database class allow for quickly migrating both tables and data from one database product to another.
* Nested transaction support - Allow for nested BeginTransaction() and Commit() calls.
* Designed for relatively painless integration into your project.

