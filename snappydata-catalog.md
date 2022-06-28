# :books: SnappyData/ConputeDB Bundle Catalog - Use Cases :books:

The online bundles can be installed by executing the `install_bundle` commands as shown below. To view use case details for each bundle, click on their image.

*The bundles listed below are sorted by bundle names, and as such, the order of bundles may change as new bundles are introduced.*

---
## 1. Debezium-Kafka SnappyData/ComputeDB Connector

This bundle integrates SnappyData/ComputeDB with Debezium for ingesting initial data and CDC records from MySQL into a SnappyData/ComputeDB cluster via a Kafka sink connector included in the `padogrid` distribution. It supports inserts, updates and deletes.

```bash
install_bundle -download bundle-snappydata-1-docker-debezium_kafka
```

[![Debezium-Kafka SnappyData/ComputeDB Connector](https://github.com/padogrid)](https://github.com/padogrid/bundle-snappydata-1-docker-debezium_kafka)

---
## 2. SnappyData Bundle Template

This bundle serves as a template for creating a new SnappyData onlne bundle.

```bash
install_bundle -download bundle-snappydata-template
```

[![SnappyData Bundle Template](https://github.com/padogrid)](https://github.com/padogrid/bundle-snappydata-template)
