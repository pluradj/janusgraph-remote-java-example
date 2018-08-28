# JanusGraph TinkerPop Remote Java Example

Simple Java example connecting to a remote Gremlin Server using JanusGraph 0.3.0 and Apache TinkerPop 3.3.3.

## Build Environment

* Java 8.0 Update 181
* Apache Maven 3.5.4

## Building and Running

Start JanusGraph pre-packaged distribution
```
bin/janusgraph.sh start
```

Build this example
```
mvn clean package
```

Run this example
```
mvn exec:java -Dexec.mainClass="pluradj.janusgraph.example.RemoteJavaExample"
```

## References

* [JanusGraph 0.3.0 Release](https://github.com/JanusGraph/janusgraph/releases/tag/v0.3.0)
* [JanusGraph Getting Started](https://docs.janusgraph.org/0.3.0/getting-started.html)
* [Apache TinkerPop: Connecting via Java](https://tinkerpop.apache.org/docs/3.3.3/reference/#connecting-via-java)
* [Apache TinkerPop 3.3.3 Javadocs](https://tinkerpop.apache.org/javadocs/3.3.3/full/)
