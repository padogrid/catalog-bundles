# :earth_americas: PadoGrid Combined Bundle Catalog - Use Cases :earth_americas:

This catalog combines all the online PadoGrid bundles. The bundles in each data grid product are grouped as follows.

- [Geode/GemFireBundle Catalog](#books-geodegemfire-bundle-catalog---use-cases-books)
- [Hazelcast IMDG Bundle Catalog](#books-hazelcast-imdg-bundle-catalog---use-cases-books)
- [Hazelcast Jet Bundle Catalog](#books-hazelcast-jet-bundle-catalog---use-cases-books)
- [SnappyData/ComputeDB Bundle Catalog](#books-snappydataconputedb-bundle-catalog---use-cases-books)
- [Coherence Bundle Catalog](#books-coherence-bundle-catalog---use-cases-books)

---

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
## 2. Bundle: mysql

The `mysql` bundle is preconfigured to synchronize Geode/GemFire with MySQL running on localhost. It includes the `mysql` cluster and `perf_test_mysql` app to quickly start up a Gedoe/GemFire cluster and run the client app to write/read to/from Geode/GemFire and MySQL.

```bash
install_bundle -download bundle-geode-1-app-perf_test_mysql-cluster-mysql
```

[![Bundle: mysql](https://github.com/padogrid/bundle-geode-1-app-perf_test_mysql-cluster-mysql/blob/master/images/db-sync.png?raw=true)](https://github.com/padogrid/bundle-geode-1-app-perf_test_mysql-cluster-mysql)

---
## 3. Bundle: Power BI

This bundle contains a Microsoft Power BI example that interfaces Power BI with Geode/GemFire via the REST API.

```bash
install_bundle -download bundle-geode-1-app-perf_test_powerbi-cluster-powerbi
```

[![Bundle: Power BI](https://github.com/padogrid/bundle-geode-1-app-perf_test_powerbi-cluster-powerbi/blob/master/images/powerbi.png?raw=true)](https://github.com/padogrid/bundle-geode-1-app-perf_test_powerbi-cluster-powerbi)

---
## 4. Bundle: WAN

The `wan` bundle includes two (2) local clusters configured with bi-directional WAN gateways. You can test the bundle immediately after installation. No configurations required.

```bash
install_bundle -download bundle-geode-1-app-perf_test_wan-cluster-ln-ny
```

[![Bundle: WAN](https://github.com/padogrid/bundle-geode-1-app-perf_test_wan-cluster-ln-ny/blob/master/images/wan-ny-ln.png?raw=true)](https://github.com/padogrid/bundle-geode-1-app-perf_test_wan-cluster-ln-ny)

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

---

# :books: Hazelcast IMDG Bundle Catalog - Use Cases :books:

The online bundles can be installed by executing the `install_bundle` commands as shown below. To view use case details for each bundle, click on their image.

*The bundles listed below are sorted by bundle names, and as such, the order of bundles may change as new bundles are introduced.*

---
## 1. Bundle: dbsched

The `dbsched` bundle is preconfigured with the Pado scheduler to periodically execute jobs that dump database tables to CSV files from which it automatically extracts column information to generate the corresponding `VersionedPortable` classes. It then transforms the CSV records to objects using the generated classes before ingesting them into Hazelcast.

```bash
install_bundle -download bundle-hazelcast-3-app-pado_dbsched-perf_test_dbsched-cluster-dbsched
```

[![Bundle: dbsched](https://github.com/padogrid/bundle-hazelcast-3-app-pado_dbsched-perf_test_dbsched-cluster-dbsched/blob/master//images/db-sched.png?raw=true)](https://github.com/padogrid/bundle-hazelcast-3-app-pado_dbsched-perf_test_dbsched-cluster-dbsched)

---
## 2. Cluster Split-Brain

This bundle provides scripts, configuration files, and apps for creating a network split-brain environment where you can test Hazelcast's split-brain capabilities.

```bash
install_bundle -download bundle-hazelcast-3-app-perf_test_sb-cluster-sb
```

[![Cluster Split-Brain](https://github.com/padogrid/bundle-hazelcast-4-app-perf_test_sb-cluster-sb/blob/master/images/split-brain.png?raw=true)](https://github.com/padogrid/bundle-hazelcast-3-app-perf_test_sb-cluster-sb)

---
## 3. App: Pado

The pado app provides a Hazelcast `Portable` class generator and CSV file import tools for Hazelcast. This bundle includes step-by-step instructions for ingesting mock data and UCI Machine Learning datasets into Hazelcast. It also includes a Pado scheduler demo that automates scheduled job executions for exporting and importing data from databases.

```bash
install_bundle -download bundle-hazelcast-3n4n5-app-pado
```

[![App: Pado](https://github.com/padogrid/bundle-hazelcast-3n4n5-app-pado/blob/master/images/app-pado-import.png?raw=true)](https://github.com/padogrid/bundle-hazelcast-3n4n5-app-pado)

---
## 4. Bundle: MySQL Sync

This bundle is preconfigured to synchronize Hazelcast with MySQL running as a Docker container. It includes the `db` cluster app to read/write from/to Hazelcast and MySQL. It also includes instructions for replacing MySQL with another database.

```bash
install_bundle -download bundle-hazelcast-3n4n5-docker-dbsync_mysql
```

[![Bundle: MySQL Sync](https://github.com/padogrid/bundle-hazelcast-3n4n5-docker-dbsync_mysql/blob/master/images/mysql-sync.png?raw=true)](https://github.com/padogrid/bundle-hazelcast-3n4n5-docker-dbsync_mysql)

---
## 5. Debezium-Hive-Kafka Hazelcast Connector

This bundle integrates Hazelcast with Debezium and Apache Hive for ingesting initial data and CDC records from MySQL into a Hazelcast cluster via a Kafka sink connector included in the `padogrid` distribution. It supports inserts, updates and deletes.

```bash
install_bundle -download bundle-hazelcast-3n4n5-docker-debezium_hive_kafka
```

[![Debezium-Hive-Kafka Hazelcast Connector](https://github.com/padogrid/bundle-hazelcast-3n4n5-docker-debezium_hive_kafka/blob/master/images/debezium-hive-kafka.jpg?raw=true)](https://github.com/padogrid/bundle-hazelcast-3n4n5-docker-debezium_hive_kafka)

---
## 6. Debezium-Kafka Hazelcast Connector

This bundle integrates Hazelcast with Debezium for ingesting initial data and CDC records from MySQL into a Hazelcast cluster via a Kafka sink connector included in the `padogrid` distribution. It supports inserts, updates and deletes.

```bash
install_bundle -download bundle-hazelcast-3n4n5-docker-debezium_kafka
```

[![Debezium-Kafka Hazelcast Connector](https://github.com/padogrid/bundle-hazelcast-3n4n5-docker-debezium_kafka/blob/master/images/debezium-kafka.png?raw=true)](https://github.com/padogrid/bundle-hazelcast-3n4n5-docker-debezium_kafka)

---
## 7. Debezium-KSQL-Kafka Hazelcast Connector

This bundle integrates Hazelcast with Debezium and Confluent KSQL and ksqlDB for ingesting initial data and CDC records from MySQL into a Hazelcast cluster via a Kafka sink connector included in the `padogrid` distribution. It supports inserts, updates and deletes.

```bash
install_bundle -download bundle-hazelcast-3n4n5-docker-debezium_ksql_kafka
```

[![Debezium-KSQL-Kafka Hazelcast Connector](https://github.com/padogrid/bundle-hazelcast-3n4n5-docker-debezium_ksql_kafka/blob/master/images/debezium-ksql-kafka.jpg?raw=true)](https://github.com/padogrid/bundle-hazelcast-3n4n5-docker-debezium_ksql_kafka)

---
## 8. Hazelcast OpenShift Helm Charts

This bundle deploys Hazelcast using Helm Charts with Prometheus metrics enabled. It also includes the PadoGrid container for ingesting mock data into the Hazelcast cluster.

```bash
install_bundle -download bundle-hazelcast-3n4n5-k8s-oc_helm
```

[![Hazelcast OpenShift Helm Charts](https://github.com/padogrid/bundle-hazelcast-3n4n5-k8s-oc_helm/blob/master/images/oc-helm.jpg?raw=true)](https://github.com/padogrid/bundle-hazelcast-3n4n5-k8s-oc_helm)

---
## 9. Hazelcast WAN Replication on OpenShift using Helm Charts

This bundle demonstrates the Hazelcast WAN topology by replicating data between two (2) Hazlecast Helm Chart clusters running on OpenShift.

```bash
install_bundle -download bundle-hazelcast-3n4n5-k8s-oc_helm_wan
```

[![Hazelcast WAN Replication on OpenShift using Helm Charts](https://github.com/padogrid/bundle-hazelcast-3n4n5-k8s-oc_helm_wan/blob/master/images/oc-helm-wan.jpg?raw=true)](https://github.com/padogrid/bundle-hazelcast-3n4n5-k8s-oc_helm_wan)

---
## 10. Hazelcast OpenShift Operator

This bundle contains OpenShift operator configuration files for deploying Hazelcast and PadoGrid. Hazelcast is deployed using the Hazelcast Operator downloaded from the `hazelcast/hazelcast-operator` repo.

```bash
install_bundle -download bundle-hazelcast-4-k8s-oc_operator
```

[![Hazelcast OpenShift Operator](https://github.com/padogrid/bundle-hazelcast-4-k8s-oc_operator/blob/master/images/oc-operator.jpg?raw=true)](https://github.com/padogrid/bundle-hazelcast-4-k8s-oc_operator)

---
## 11. Hazelcast WAN Replication on OpenShift using Operator

This bundle demonstrates the Hazelcast WAN topology by replicating data between two (2) Hazlecast Operator clusters running on OpenShift.

```bash
install_bundle -download bundle-hazelcast-4-k8s-oc_operator_wan
```

[![Hazelcast WAN Replication on OpenShift using Operator](https://github.com/padogrid/bundle-hazelcast-4-k8s-oc_operator_wan/blob/master/images/oc-operator-wan.jpg?raw=true)](https://github.com/padogrid/bundle-hazelcast-4-k8s-oc_operator_wan)

---
## 12. Hazelcast Kryo/Avro Code Generator

This bundle provides step-by-step instructions for generating and deploying Avro and `KryoSerializer` in Hazelcast. Using PadoGrid's code generator, you can on the fly generate and deploy Avro wrapper classes and the correspoinding Kryo serializer.

```bash
install_bundle -download bundle-hazelcast-4n5-app-kryo_codegen
```

[![Hazelcast Kryo/Avro Code Generator](https://github.com/padogrid/bundle-hazelcast-4n5-app-kryo_codegen/blob/master/images/app-kryo-codegen.jpg?raw=true)](https://github.com/padogrid/bundle-hazelcast-4n5-app-kryo_codegen)

---
## 13. Cluster Split-Brain

This bundle provides scripts, configuration files, and apps for creating a Hazelcast 4.x network split-brain environment where you can test Hazelcast's split-brain capabilities.

```bash
install_bundle -download bundle-hazelcast-4n5-app-perf_test_sb-cluster-sb
```

[![Cluster Split-Brain](https://github.com/padogrid/bundle-hazelcast-4n5-app-perf_test_sb-cluster-sb/blob/master/images/split-brain.png?raw=true)](https://github.com/padogrid/bundle-hazelcast-4n5-app-perf_test_sb-cluster-sb)

---
## 14. Session Expiration Management Plugin

This bundle provides a plugin that expires session objects in a given map and their relevant entries in other Hazelcast maps. The plugin also supports session expirations over the WAN (See [bundle-hazelcast-4n5-cluster-session-wan](https://github.com/padogrid/bundle-hazelcast-4n5-cluster-session-wan).)

```bash
install_bundle -download bundle-hazelcast-4n5-cluster-session
```

[![Session Expiration Management Plugin](https://github.com/padogrid/bundle-hazelcast-4n5-cluster-session/blob/master/images/session.jpg?raw=true)](https://github.com/padogrid/bundle-hazelcast-4n5-cluster-session)

---
## 15. Session Expiration in WAN Environment

This bundle demonstrates the session expiration plugin in a WAN environment. It incorporates the session expiration plugin included in [bundle-hazelcast-4n5-cluster-session](https://github.com/padogrid/bundle-hazelcast-4n5-cluster-session.git) and the Sorint.lab's `IpDiscoveryStrategy` plugin.

```bash
install_bundle -download bundle-hazelcast-4n5-cluster-session-wan
```

[![Session Expiration in WAN Environment](https://github.com/padogrid/bundle-hazelcast-4n5-cluster-session-wan/blob/master/images/wan-session-expiration.png?raw=true)](https://github.com/padogrid/bundle-hazelcast-4n5-cluster-session-wan)

---
## 16. Hazelcast Bundle Template

This bundle serves as a template for creating a new Hazelcast onlne bundle.

```bash
install_bundle -download bundle-hazelcast-template
```

[![Hazelcast Bundle Template](https://github.com/padogrid/bundle-hazelcast-template/blob/master/?raw=true)](https://github.com/padogrid/bundle-hazelcast-template)

---
## 17. Rolling Upgrade Training

As part of the Rolling Upgrade lab of Hazelcast Operations Training, this bundle includes a cluster and an app preconfigured to run with Hazelcast Enterprise 3.11.x which must be installed separately.

```bash
install_bundle -download bundle-hazelcast-training-3.11-app-perf_test_v3.11-cluster-v3.11
```

[![Rolling Upgrade Training](https://github.com/padogrid/bundle-hazelcast-training-3.11-app-perf_test_v3.11-cluster-v3.11/blob/master/?raw=true)](https://github.com/padogrid/bundle-hazelcast-training-3.11-app-perf_test_v3.11-cluster-v3.11)

---
## 18. IMDG Cluster: openssl

As part of the TLS/SSL lab of Hazelcast Operations Training, this bundle includes the `openssl` cluster preconfigured to enable OpenSSL/BoringSSL.

```bash
install_bundle -download bundle-hazelcast-training-3n4n5-app-perf_test_openssl-cluster-openssl
```

[![IMDG Cluster: openssl](https://github.com/padogrid/bundle-hazelcast-training-3n4n5-app-perf_test_openssl-cluster-openssl/blob/master/images/openssl-cluster.jpg?raw=true)](https://github.com/padogrid/bundle-hazelcast-training-3n4n5-app-perf_test_openssl-cluster-openssl)

---
## 19. IMDG Cluster: ssl

As part of the TLS/SSL lab of Hazelcast Operations Training, the `ssl` cluster has been preconfigured to enable SSL. It contains scripts to create both private and trust keystores that contain both member and client keys and certificates.

```bash
install_bundle -download bundle-hazelcast-training-3n4n5-app-perf_test_ssl-cluster-ssl
```

[![IMDG Cluster: ssl](https://github.com/padogrid/bundle-hazelcast-training-3n4n5-app-perf_test_ssl-cluster-ssl/blob/master/images/ssl-cluster.jpg?raw=true)](https://github.com/padogrid/bundle-hazelcast-training-3n4n5-app-perf_test_ssl-cluster-ssl)

---

# :books: Hazelcast Jet Bundle Catalog - Use Cases :books:

The online bundles can be installed by executing the `install_bundle` commands as shown below. To view use case details for each bundle, click on their image.

*The bundles listed below are sorted by bundle names, and as such, the order of bundles may change as new bundles are introduced.*

---
## 1. Jet Cluster: trade

The `trade` cluster bundle installs a Jet cluster that includes the `build_app` script to clone and build the `realtime-trade-monitor` project maintained at the GitHub URL shown below.

```bash
install_bundle -download bundle-jet-3-cluster-trade
```

[![Jet Cluster: trade](https://github.com/padogrid/bundle-jet-3-cluster-trade/blob/master//images/jet-trade.png?raw=true)](https://github.com/padogrid/bundle-jet-3-cluster-trade)

---
## 2. Jet App: trade-monitor

The `trade-monitor` app bundle installs the `trade-monitor` demo as part of the `hazelcast/hazelcast-platform-demos` GitHub repo maintained by Hazelcast.

```bash
install_bundle -download bundle-jet-4-app-trade
```

[![Jet App: trade-monitor](https://github.com/padogrid/bundle-jet-4-app-trade/blob/master/images/jet-trade-monitor.jpg?raw=true)](https://github.com/padogrid/bundle-jet-4-app-trade)

---
## 3. Jet CDC Tutorial

The `cdc_tutorial` bundle wraps the CDC tutorial available from the Hazelcast site [https://jet-start.sh/docs/tutorials/cdc](https://jet-start.sh/docs/tutorials/cdc).

```bash
install_bundle -download bundle-jet-4-docker-cdc_tutorial
```

[![Jet CDC Tutorial](https://github.com/padogrid/bundle-jet-4-docker-cdc_tutorial/blob/master//images/jet-cdc-tutorial.png?raw=true)](https://github.com/padogrid/bundle-jet-4-docker-cdc_tutorial)

---

# :books: SnappyData/ConputeDB Bundle Catalog - Use Cases :books:

The online bundles can be installed by executing the `install_bundle` commands as shown below. To view use case details for each bundle, click on their image.

*The bundles listed below are sorted by bundle names, and as such, the order of bundles may change as new bundles are introduced.*

---
## 1. Debezium-Kafka SnappyData/ComputeDB Connector

This bundle integrates SnappyData/ComputeDB with Debezium for ingesting initial data and CDC records from MySQL into a SnappyData/ComputeDB cluster via a Kafka sink connector included in the `padogrid` distribution. It supports inserts, updates and deletes.

```bash
install_bundle -download bundle-snappydata-1-docker-debezium_kafka
```

[![Debezium-Kafka SnappyData/ComputeDB Connector](https://github.com/padogrid/bundle-snappydata-1-docker-debezium_kafka/blob/master//images/debezium-kafka.jpg?raw=true)](https://github.com/padogrid/bundle-snappydata-1-docker-debezium_kafka)

---
## 2. SnappyData Bundle Template

This bundle serves as a template for creating a new SnappyData onlne bundle.

```bash
install_bundle -download bundle-snappydata-template
```

[![SnappyData Bundle Template](https://github.com/padogrid/bundle-snappydata-template/blob/master/?raw=true)](https://github.com/padogrid/bundle-snappydata-template)

---

# :books: Coherence Bundle Catalog - Use Cases :books:

The online bundles can be installed by executing the `install_bundle` commands as shown below. To view use case details for each bundle, click on their image.

*The bundles listed below are sorted by bundle names, and as such, the order of bundles may change as new bundles are introduced.*

---
## 1. Coherence Bundle Template

This bundle serves as a template for creating a new Coherence onlne bundle.

```bash
install_bundle -download bundle-coherence-template
```

[![Coherence Bundle Template](https://github.com/padogrid/bundle-coherence-template/blob/master/?raw=true)](https://github.com/padogrid/bundle-coherence-template)
