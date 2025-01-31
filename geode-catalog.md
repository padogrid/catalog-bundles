![PadoGrid](https://github.com/padogrid/padogrid/raw/develop/images/padogrid-3d-16x16.png) [*PadoGrid*](https://github.com/padogrid) | [*Catalogs*](https://github.com/padogrid/catalog-bundles/blob/master/all-catalog.md) | [*Manual*](https://github.com/padogrid/padogrid/wiki) | [*FAQ*](https://github.com/padogrid/padogrid/wiki/faq) | [*Releases*](https://github.com/padogrid/padogrid/releases) | [*Templates*](https://github.com/padogrid/padogrid/wiki/Using-Bundle-Templates) | [*Pods*](https://github.com/padogrid/padogrid/wiki/Understanding-Padogrid-Pods) | [*Kubernetes*](https://github.com/padogrid/padogrid/wiki/Kubernetes) | [*Docker*](https://github.com/padogrid/padogrid/wiki/Docker) | [*Apps*](https://github.com/padogrid/padogrid/wiki/Apps) | [*Quick Start*](https://github.com/padogrid/padogrid/wiki/Quick-Start)

---

# :books: Geode/GemFire Bundle Catalog :books:

The online bundles can be installed by executing the `install_bundle` commands as shown below. To view use case details for each bundle, click on their image.

*The bundles listed below are sorted by bundle names, and as such the order of bundles may change as new bundles are introduced.*

---
## [1. Geode/GemFire Kryo Code Generator](https://github.com/padogrid/bundle-geode-1-app-kryo_codegen)

This bundle provides step-by-step instructions for generating and deploying Avro and `KryoSerializer` in Geode/GemFire. Using PadoGrid's code generator, you can on the fly generate and deploy Avro wrapper classes and the corresponding Kryo serializer.

```bash
install_bundle -download bundle-geode-1-app-kryo_codegen
```

[![Geode/GemFire Kryo Code Generator](https://github.com/padogrid/bundle-geode-1-app-kryo_codegen/blob/master/images/geode-app-kryo-codegen.jpg?raw=true)](https://github.com/padogrid/bundle-geode-1-app-kryo_codegen)

---
## [2. Bundle: Power BI](https://github.com/padogrid/bundle-geode-1-app-perf_test_powerbi-cluster-powerbi)

This bundle contains a Microsoft Power BI example that interfaces Power BI with Geode/GemFire via the REST API. This article can be viewed in your browser by running the following: ```bash show_bundle bundle-geode-1-app-perf_test_powerbi-cluster-powerbi ```

```bash
install_bundle -download bundle-geode-1-app-perf_test_powerbi-cluster-powerbi
```

[![Bundle: Power BI](https://github.com/padogrid/bundle-geode-1-app-perf_test_powerbi-cluster-powerbi/blob/master/images/powerbi.png?raw=true)](https://github.com/padogrid/bundle-geode-1-app-perf_test_powerbi-cluster-powerbi)

---
## [3. Geode/GemFire Split-Brain](https://github.com/padogrid/bundle-geode-1-app-perf_test_sb-cluster-sb)

This bundle provides scripts, configuration files, and apps for creating a Geode/GemFire network split-brain environment where you can test Geode/GemFire split-brain capabilities. Although it focuses on split-brain issues, the scripts provided cover any system failures.

```console
install_bundle -download -workspace bundle-geode-1-app-perf_test_sb-cluster-sb
```

[![Geode/GemFire Split-Brain](https://github.com/padogrid/bundle-geode-1-app-perf_test_sb-cluster-sb/blob/master/images/split-brain-Type-2.drawio.png?raw=true)](https://github.com/padogrid/bundle-geode-1-app-perf_test_sb-cluster-sb)

---
## [4. Geode/GemFire WAN](https://github.com/padogrid/bundle-geode-1-app-perf_test_wan-cluster-ln-ny)

The `wan` bundle includes two (2) local clusters configured with bidirectional WAN gateways. You can test the bundle immediately after installation. No configurations required. To understand how the clusters are configured, please see the following WAN example. It provides step-by-step instructions for creating and running WAN enabled clusters from scratch. [Geode/GemFire WAN Example](https://github.com/padogrid/padogrid/wiki/Geode-WAN-Example)

```bash
# To run
install_bundle -download -workspace bundle-geode-1-app-perf_test_wan-cluster-ln-ny

# To run and/or check in
install_bundle -checkout bundle-geode-1-app-perf_test_wan-cluster-ln-ny
```

[![Geode/GemFire WAN](https://github.com/padogrid/bundle-geode-1-app-perf_test_wan-cluster-ln-ny/blob/master/images/wan-ny-ln.png?raw=true)](https://github.com/padogrid/bundle-geode-1-app-perf_test_wan-cluster-ln-ny)

---
## [5. GemFire/Geode and MySQL Sync](https://github.com/padogrid/bundle-geode-1-docker-dbsync_mysql)

This bundle is preconfigured to synchronize Geode/GemFire with MySQL running as a Docker container. It includes the `db` cluster app to read/write from/to Geode/GemFire and MySQL. It also includes instructions for replacing MySQL with another database.

```bash
# Instal in the current workspace
install_bundle -download bundle-geode-1-docker-dbsync_mysql

# Install in the new bundle default workspace
install_bundle -download -workspace bundle-geode-1-docker-dbsync_mysql

# Install in the new bundle default workspace with git intact
install_bundle -checkout bundle-geode-1-docker-dbsync_mysql
```

[![GemFire/Geode and MySQL Sync](https://github.com/padogrid/bundle-geode-1-docker-dbsync_mysql/blob/master/images/mysql-sync.png?raw=true)](https://github.com/padogrid/bundle-geode-1-docker-dbsync_mysql)

---
## [6. Debezium-Hive-Kafka Geode Connector](https://github.com/padogrid/bundle-geode-1-docker-debezium_hive_kafka)

This bundle integrates Geode with Debezium and Apache Hive for ingesting initial data and CDC records from MySQL into a Geode cluster via a Kafka sink connector included in the `padogrid` distribution. It supports inserts, updates and deletes.

```bash
install_bundle -download bundle-geode-1-docker-debezium_hive_kafka
```

[![Debezium-Hive-Kafka Geode Connector](https://github.com/padogrid/bundle-geode-1-docker-debezium_hive_kafka/blob/master/images/geode-debezium-hive-kafka.jpg?raw=true)](https://github.com/padogrid/bundle-geode-1-docker-debezium_hive_kafka)

---
## [7. Debezium-Kafka Geode Connector](https://github.com/padogrid/bundle-geode-1-docker-debezium_kafka)

This bundle integrates Geode with Debezium for ingesting initial data and CDC records from MySQL into a Geode cluster via a Kafka sink connector included in the `padogrid` distribution. It supports inserts, updates and deletes.

```bash
install_bundle -download bundle-geode-1-docker-debezium_kafka
```

[![Debezium-Kafka Geode Connector](https://github.com/padogrid/bundle-geode-1-docker-debezium_kafka/blob/master/images/debezium-kafka.png?raw=true)](https://github.com/padogrid/bundle-geode-1-docker-debezium_kafka)

---
## [8. Debezium-KSQL-Kafka Geode Connector](https://github.com/padogrid/bundle-geode-1-docker-debezium_ksql_kafka)

This bundle integrates Geode with Debezium and Confluent KSQL for ingesting initial data and CDC records from MySQL into a Geode cluster via a Kafka sink connector included in the `padogrid` distribution. It supports inserts, updates and deletes.

```bash
install_bundle -download bundle-geode-1-docker-debezium_ksql_kafka
```

[![Debezium-KSQL-Kafka Geode Connector](https://github.com/padogrid/bundle-geode-1-docker-debezium_ksql_kafka/blob/master/images/geode-debezium-ksql-kafka.jpg?raw=true)](https://github.com/padogrid/bundle-geode-1-docker-debezium_ksql_kafka)

---
## [9. Debezium-ksqlDB-Confluent Geode Connector](https://github.com/padogrid/bundle-geode-1-docker-debezium_ksqldb_confluent)

This bundle integrates Geode with Debezium and Confluent ksqlDB for ingesting initial data and CDC records from MySQL into Kafka and Geode via a Kafka sink connector included in the `padogrid` distribution.

```bash
install_bundle -download -workspace bundle-geode-1-docker-debezium_ksqldb_confluent
```

[![Debezium-ksqlDB-Confluent Geode Connector](https://github.com/padogrid/bundle-geode-1-docker-debezium_ksqldb_confluent/blob/master/images/geode-debezium-confluent.jpg?raw=true)](https://github.com/padogrid/bundle-geode-1-docker-debezium_ksqldb_confluent)

---
## [10. Geode Bundle Template](https://github.com/padogrid/bundle-geode-template)

This bundle serves as a template for creating a new Geode onlne bundle.

```bash
install_bundle -download bundle-geode-template
```

[![Geode Bundle Template](https://github.com/padogrid/padogrid/wiki/Quick-Start)](https://github.com/padogrid/bundle-geode-template)

---

![PadoGrid](https://github.com/padogrid/padogrid/raw/develop/images/padogrid-3d-16x16.png) [*PadoGrid*](https://github.com/padogrid) | [*Catalogs*](https://github.com/padogrid/catalog-bundles/blob/master/all-catalog.md) | [*Manual*](https://github.com/padogrid/padogrid/wiki) | [*FAQ*](https://github.com/padogrid/padogrid/wiki/faq) | [*Releases*](https://github.com/padogrid/padogrid/releases) | [*Templates*](https://github.com/padogrid/padogrid/wiki/Using-Bundle-Templates) | [*Pods*](https://github.com/padogrid/padogrid/wiki/Understanding-Padogrid-Pods) | [*Kubernetes*](https://github.com/padogrid/padogrid/wiki/Kubernetes) | [*Docker*](https://github.com/padogrid/padogrid/wiki/Docker) | [*Apps*](https://github.com/padogrid/padogrid/wiki/Apps) | [*Quick Start*](https://github.com/padogrid/padogrid/wiki/Quick-Start)
