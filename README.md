# learning-mysql


Introduction

        MySQL Overview, Products, Services
        MySQL Services and Support
        Supported Operating Services
        Training Curriculum Paths
        MySQL Documentation Resources

MySQL Architecture

        The client/server model
        Communication protocols
        The SQL Layer
        The Storage Layer
        How the server supports storage engines
        How MySQL uses memory and disk space
        The MySQL plug-in interface

System Administration

        Choosing between types of MySQL distributions
        Installing the MySQL Server
        The MySQL Server installation file structure
        Starting and stopping the MySQL server
        Upgrading MySQL
        Running multiple MySQL servers on a single host

Server Configuration

        MySQL server configuration options
        System variables
        SQL Modes
        Available log files
        Binary logging

Clients and Tools

        Available clients for administrative tasks
        MySQL administrative clients
        The mysql command-line client
        The mysqladmin command-line client
        The MySQL Workbench graphical client
        MySQL tools
        Available APIs (drivers and connectors)

Data Types

        Major categories of data types
        Meaning of NULL
        Column attributes
        Character set usage with data types
        Choosing an appropriate data type

Obtaining Metadata

        Available metadata access methods
        Structure of INFORMATION_SCHEMA
        Using the available commands to view metadata
        Differences between SHOW statements and INFORMATION_SCHEMA tables
        The mysqlshow client program
        Using INFORMATION_SCHEMA queries to create shell commands and SQL statements

Transactions and Locking

        Using transaction control statement to run multiple SQL statements concurrently
        The ACID properties of transactions
        Transaction isolation levels
        Using locking to protect transactions

Storage Engines

        Storage engines in MySQL
        InnoDB storage engine
        InnoDB system and file-per-table tablespaces
        NoSQL and the Memcached API
        Configuring tablespaces efficiently
        Using foreign keys to attain referential integrity
        InnoDB locking
        Features of available storage engines

Partitioning

        Partitioning and its use in MySQL
        Reasons for using partitioning
        Types of partitioning
        Creating partitioned tables
        Subpartitioning
        Obtaining partition metadata
        Modifying partitions to improve performance
        Storage Engine Support of Partitioning

User Management

        Requirements for user authentication
        Using SHOW PROCESSLIST to show which threads are running
        Creating, modifying and dropping user accounts
        Alternative authentication plugins
        Requirements for user authorization
        Levels of access privileges for users
        Types of privileges
        Granting, modifying and revoking user privileges

Security

        Recognizing common security risks
        Security risks specific to the MySQL installation
        Security problems and counter-measures for network, operating system, filesystem and users
        Protecting your data
        Using SSL for secure MySQL server connections
        How SSH enables a secure remote connection to the MySQL server
        Finding additional information for common security issues

Table Maintenance

        Types of table maintenance operations
        SQL statements for table maintenance
        Client and utility programs for table maintenance
        Maintaining tables for other storage engines
        Exporting and Importing Data
        Exporting Data
        Importing Data

Programming Inside MySQL

        Creating and executing Stored Routines
        Describing stored routine execution security
        Creating and executing triggers
        Creating, altering and dropping events
        Event execution scheduling

MySQL Backup and Recovery

        Backup basics
        Types of backup
        Backup tools and utilities
        Making binary and text backups
        Role of log and status files in backups
        Data Recovery

Replication

        Managing the MySQL Binary Log
        MySQL replication threads and files
        Setting up a MySQL Replication Environment
        Designing Complex Replication Topologies
        Multi-Master and Circular Replication
        Performing a Controlled Switchover
        Monitoring and Troubleshooting MySQL Replication
        Replication with Global Transaction Identifiers (GTIDs)

Introduction to Performance Tuning

        Using EXPLAIN to Analyze Queries
        General Table Optimizations
        Monitoring status variables that affect performance
        Setting and Interpreting MySQL server Variables
        Overview of Performance Schema