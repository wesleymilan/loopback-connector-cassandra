## loopback-connector-cassandra

**NOTE: THIS MODULE IS PRE-RELEASE **

Cassandra connector for LoopBack that uses an data agnostic storage.

## Usage

Put the library inside node_modules of your application
Include require('../node_modules/loopback-connector-cassandra'); on the top of your server.js

## Datasources.json
Your datasource have to look like this
{
  "db": {
    "contactPoints": ["127.0.0.1", node2, node3],
    "port": 9042,
    "keyspace": "my_database_keyspace",
    "connector": "cassandra"
  }
}

Don't forget to instal cassandra-driver.

## Running tests

Make sure you have redis server running on default port, then run

    npm test


## MIT License

