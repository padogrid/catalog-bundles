# :books: Geode/GemFire Bundle Catalog - Use Cases :books:

The online bundles can be installed by executing the `install_bundle` commands as shown below. To view use case details for each bundle, click on their image.

*The bundles listed below are sorted by bundle names, and as such, the order of bundles may change as new bundles are introduced.*

---
## 1. Geode/GemFire Kryo Code Generator

This bundle provides step-by-step instructions for generating and deploying Avro and `KryoSerializer` in Geode/GemFire. Using PadoGrid's code generator, you can on the fly generate and deploy Avro wrapper classes and the corresponding Kryo serializer.

```bash
install_bundle -download bundle-geode-1-app-kryo_codegen
```

[![Geode/GemFire Kryo Code Generator](https://github.com/padogrid/bundle-geode-1-app-kryo_codegen/blob/master/images/geode-app-kryo-codegen.jpg?raw=true)](https://github.com/padogrid/bundle-geode-1-app-kryo_codegen)

---
## 2. Bundle: Power BI

This bundle contains a Microsoft Power BI example that interfaces Power BI with Geode/GemFire via the REST API.

```bash
install_bundle -download bundle-geode-1-app-perf_test_powerbi-cluster-powerbi
```

[![Bundle: Power BI](https://github.com/padogrid/bundle-geode-1-app-perf_test_powerbi-cluster-powerbi/blob/master/images/powerbi.png?raw=true)](https://github.com/padogrid/bundle-geode-1-app-perf_test_powerbi-cluster-powerbi)

---
## 3. Bundle: WAN

The `wan` bundle includes two (2) local clusters configured with bidirectional WAN gateways. You can test the bundle immediately after installation. No configurations required.

```bash
install_bundle -download bundle-geode-1-app-perf_test_wan-cluster-ln-ny
```

[![Bundle: WAN](https://github.com/padogrid/bundle-geode-1-app-perf_test_wan-cluster-ln-ny/blob/master/images/wan-ny-ln.png?raw=true)](https://github.com/padogrid/bundle-geode-1-app-perf_test_wan-cluster-ln-ny)

---
## 4. GemFire/Geode and MySQL Sync

This bundle is preconfigured to synchronize Geode/GemFire with MySQL running as a Docker container. It includes the `db` cluster app to read/write from/to Geode/GemFire and MySQL. It also includes instructions for replacing MySQL with another database.

```bash
install_bundle -download bundle-geode-1-docker-dbsync_mysql
```

[![GemFire/Geode and MySQL Sync](https://github.com/padogrid/bundle-geode-1-docker-dbsync_mysql/blob/master/images/mysql-sync.png?raw=true)](https://github.com/padogrid/bundle-geode-1-docker-dbsync_mysql)

---
## 5. Debezium-Hive-Kafka Geode Connector

This bundle integrates Geode with Debezium and Apache Hive for ingesting initial data and CDC records from MySQL into a Geode cluster via a Kafka sink connector included in the `padogrid` distribution. It supports inserts, updates and deletes.

```bash
install_bundle -download bundle-geode-1-docker-debezium_hive_kafka
```

[![Debezium-Hive-Kafka Geode Connector](https://github.com/padogrid/bundle-geode-1-docker-debezium_hive_kafka/blob/master/images/geode-debezium-hive-kafka.jpg?raw=true)](https://github.com/padogrid/bundle-geode-1-docker-debezium_hive_kafka)

---
## 6. Debezium-Kafka Geode/GemFire Connector

This bundle integrates Geode/GemFire with Debezium for ingesting initial data and CDC records from MySQL into a Geode/GemFire cluster via a Kafka sink connector included in the `padogrid` distribution. It supports inserts, updates and deletes.

```bash
install_bundle -download bundle-geode-1-docker-debezium_kafka
```

[![Debezium-Kafka Geode/GemFire Connector](https://github.com/padogrid/bundle-geode-1-docker-debezium_kafka/blob/master/images/debezium-kafka.png?raw=true)](https://github.com/padogrid/bundle-geode-1-docker-debezium_kafka)

---
## 7. Debezium-KSQL-Kafka Geode Connector

This bundle integrates Geode with Debezium and Confluent KSQL for ingesting initial data and CDC records from MySQL into a Geode cluster via a Kafka sink connector included in the `padogrid` distribution. It supports inserts, updates and deletes.

```bash
install_bundle -download bundle-geode-1-docker-debezium_ksql_kafka
```

[![Debezium-KSQL-Kafka Geode Connector](https://github.com/padogrid/bundle-geode-1-docker-debezium_ksql_kafka/blob/master/images/geode-debezium-ksql-kafka.jpg?raw=true)](https://github.com/padogrid/bundle-geode-1-docker-debezium_ksql_kafka)

---
## 8. Debezium-ksqlDB-Confluent Geode Connector

This bundle integrates Geode with Debezium and Confluent ksqlDB for ingesting initial data and CDC records from MySQL into Kafka and Geode via a Kafka sink connector included in the `padogrid` distribution.

```bash
install_bundle -download bundle-geode-1-docker-debezium_ksqldb_confluent
```

[![Debezium-ksqlDB-Confluent Geode Connector](https://github.com/padogrid/bundle-geode-1-docker-debezium_ksqldb_confluent/blob/master/images/geode-debezium-confluent.jpg?raw=true)](https://github.com/padogrid/bundle-geode-1-docker-debezium_ksqldb_confluent)

---
## 9. Geode Bundle Template

This bundle serves as a template for creating a new Geode onlne bundle.

```bash
install_bundle -download bundle-geode-template
```

[![Geode Bundle Template](https://github.com/padogrid/bundle-geode-template/blob/master/?raw=true)](https://github.com/padogrid/bundle-geode-template)
