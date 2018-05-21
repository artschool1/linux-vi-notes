* Kafka is a distributed streaming platform.
    * a streaming platform has three capabilities
        * Publish and subscribe to streams of records, similar to a message queue or enterprise messaging system.
        * Store streams of records in a fault-tolerant durable way.
        * Process streams of records as they occur.

* Core Concepts
    * Kafka is run as a cluster on one or more servers that can span multiple datacenters
    * The Kafka cluster stores streams of *RECORDS*
    * Each record consists of a key, a value, and a time stamp.
* APIs
    * Producer - allows an app to publish stream of records to one *or more* Kafka topics
    * Consumer - allows an application to subscribe to one or more topics and process the stream of records produced
    * Streams - allows an app to act as a stream processor, consuming an input stream from one or more topics
    * Connector - allows building and running reusable producers or consumers that connect Kafka topics to existing
    * applications or data systems
        * example: a connector to a relational DB might capture every change to a table.
    * uses TCP protocol. java is provided but Avalible in many languages
* Topics and Logs
    


Kafka runs on Zookeeper Server.


