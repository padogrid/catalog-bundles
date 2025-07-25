![PadoGrid](https://github.com/padogrid/padogrid/raw/develop/images/padogrid-3d-16x16.png) [*PadoGrid*](https://github.com/padogrid) | [*Catalogs*](https://github.com/padogrid/catalog-bundles/blob/master/all-catalog.md) | [*Manual*](https://github.com/padogrid/padogrid/wiki) | [*FAQ*](https://github.com/padogrid/padogrid/wiki/faq) | [*Releases*](https://github.com/padogrid/padogrid/releases) | [*Templates*](https://github.com/padogrid/padogrid/wiki/Using-Bundle-Templates) | [*Pods*](https://github.com/padogrid/padogrid/wiki/Understanding-Padogrid-Pods) | [*Kubernetes*](https://github.com/padogrid/padogrid/wiki/Kubernetes) | [*Docker*](https://github.com/padogrid/padogrid/wiki/Docker) | [*Apps*](https://github.com/padogrid/padogrid/wiki/Apps) | [*Quick Start*](https://github.com/padogrid/padogrid/wiki/Quick-Start)

---

# :earth_americas: PadoGrid Bundle Catalogs :earth_americas:

*Bundles represent fully implemented use cases.* This page lists all of the open source PadoGrid bundles. The bundles in each product are grouped as follows.

- [Generic (none) Catalog](#books-generic-none-bundle-catalog-books)
- [GemFire Catalog](#books-gemfire-bundle-catalog-books)
- [Geode/GemFire Catalog](#books-geodegemfire-bundle-catalog-books)
- [Hazelcast Catalog](#books-hazelcast-bundle-catalog-books)
- [Kafka Catalog](#books-kafka-bundle-catalog-books)
- [Kafka Confluent Catalog](#books-kafka-confluent-bundle-catalog-books)
- [Mosquitto Catalog](#books-mosquitto-bundle-catalog-books)
- [SnappyData/ComputeDB Catalog](#books-snappydataconputedb-bundle-catalog-books)
- [Coherence Catalog](#books-coherence-bundle-catalog-books)

---

# :books: Generic (none) Bundle Catalog :books:

The online bundles can be installed by executing the `install_bundle` commands as shown below. To view use case details for each bundle, click on their image.

*The bundles listed below are sorted by bundle names, and as such the order of bundles may change as new bundles are introduced.*

---
## [1. Data Feed Simulator](https://github.com/padogrid/bundle-none-app-simulator)

This bundle includes a data feed simulator for generating continous numerical data for MQTT, GemFire/Geode, and Hazelcast.

```bash
install_bundle -download bundle-none-app-simulator
```

[![Data Feed Simulator](https://github.com/padogrid/bundle-none-app-simulator/blob/master/images/igloo.png?raw=true)](https://github.com/padogrid/bundle-none-app-simulator)

---
## [2. IMDG Product Benchmark Tests](https://github.com/padogrid/bundle-none-imdg-benchmark-tests)

This bundle provides step-by-step instructions for creating a test environment and conducting benchmark tests on IMDG products.

```bash
install_bundle -download -workspace bundle-none-imdg-benchmark-tests
```

[![IMDG Product Benchmark Tests](https://github.com/padogrid/bundle-none-imdg-benchmark-tests/blob/master/images/benchmark-clusters.png?raw=true)](https://github.com/padogrid/bundle-none-imdg-benchmark-tests)

---
## [3. Generic (none) Bundle Template](https://github.com/padogrid/bundle-none-template)

This bundle serves as a template for creating a new generic onlne bundle.

```bash
install_bundle -download bundle-none-template
```

[![Generic (none) Bundle Template](https://github.com/padogrid/padogrid/wiki/Quick-Start)](https://github.com/padogrid/bundle-none-template)

---
## [4. Configuring HAProxy for TLS Termination - Mosquitto, Grafana, Prometheus, Hazelcast Management Center](https://github.com/padogrid/bundle-none-tutorial-docker-haproxy)

This bundle walks through steps involved in configuring a TLS termination proxy to secure Mosquitto, Grafana, Prometheus, and Hazelcast Management Center using HAProxy.

```bash
install_bundle -download -workspace haproxy bundle-none-tutorial-docker-haproxy
```

[![Configuring HAProxy for TLS Termination - Mosquitto, Grafana, Prometheus, Hazelcast Management Center](https://github.com/padogrid/bundle-none-tutorial-docker-haproxy/blob/master/images/haproxy.drawio.png?raw=true)](https://github.com/padogrid/bundle-none-tutorial-docker-haproxy)

---
## [5. PadoGrid Tutorial](https://github.com/padogrid/bundle-none-tutorial-padogrid)

This tutorial bundle covers PadoGrid essentials.

```bash
install_bundle -download -workspace bundle-none-tutorial-padogrid
```

[![PadoGrid Tutorial](https://github.com/padogrid/bundle-none-tutorial-padogrid/blob/master/images/padogrid-tutorial.drawio.png?raw=true)](https://github.com/padogrid/bundle-none-tutorial-padogrid)

---

# :books: GemFire Bundle Catalog :books:

The online bundles can be installed by executing the `install_bundle` commands as shown below. To view use case details for each bundle, click on their image.

*The bundles listed below are sorted by bundle names, and as such the order of bundles may change as new bundles are introduced.*

---
## [1. GemFire Multi-Cluster Grafana Demo](https://github.com/padogrid/bundle-gemfire-10-cluster-wan-app-grafana)

This bundle demonstrates Grafana capabilities of monitoring five (5) GemFire clusters. It includes three (3) independent clusters and two (2) bi-directional WAN clusters along with a workflow simulator. ✏️ *This workspace bundle automatically installs the `grafana` app included in PadoGrid 1.0.2+ and supplemental scripts for driving the demo.* Please see [Release Notes](RELEASE_NOTES.md) for change logs.

```bash
install_bundle -init -checkout bundle-gemfire-10-cluster-wan-app-grafana
```

[![GemFire Multi-Cluster Grafana Demo](https://github.com/padogrid/bundle-gemfire-10-cluster-wan-app-grafana/blob/master/images/multi-clusters.drawio.png?raw=true)](https://github.com/padogrid/bundle-gemfire-10-cluster-wan-app-grafana)

---
## [2. GemFire Bundle Template](https://github.com/padogrid/bundle-gemfire-template)

This bundle serves as a template for creating a new GemFire onlne bundle.

```bash
install_bundle -download bundle-gemfire-template
```

[![GemFire Bundle Template](https://github.com/padogrid/padogrid/wiki/Quick-Start)](https://github.com/padogrid/bundle-gemfire-template)

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

# :books: Hazelcast Bundle Catalog :books:

The online bundles can be installed by executing the `install_bundle` commands as shown below. To view use case details for each bundle, click on their image.

*The bundles listed below are sorted by bundle names, and as such the order of bundles may change as new bundles are introduced.*

---
## [1. Hazelcast Split-Brain](https://github.com/padogrid/bundle-hazelcast-3-app-perf_test_sb-cluster-sb)

This bundle provides scripts, configuration files, and apps for creating a network split-brain environment where you can test Hazelcast's split-brain capabilities.

```console
install_bundle -download bundle-hazelcast-3-app-perf_test_sb-cluster-sb
```

[![Hazelcast Split-Brain](https://github.com/padogrid/bundle-hazelcast-4-app-perf_test_sb-cluster-sb/blob/master/images/split-brain.png?raw=true)](https://github.com/padogrid/bundle-hazelcast-3-app-perf_test_sb-cluster-sb)

---
## [2. App: Pado](https://github.com/padogrid/bundle-hazelcast-3n4n5-app-pado)

The pado app provides a Hazelcast `Portable` class generator and CSV file import tools for Hazelcast. This bundle includes step-by-step instructions for ingesting mock data and UCI Machine Learning datasets into Hazelcast. It also includes a Pado scheduler demo that automates scheduled job executions for exporting and importing data from databases.

```bash
install_bundle -download bundle-hazelcast-3n4n5-app-pado
```

[![App: Pado](https://github.com/padogrid/bundle-hazelcast-3n4n5-app-pado/blob/master/images/app-pado-import.png?raw=true)](https://github.com/padogrid/bundle-hazelcast-3n4n5-app-pado)

---
## [3. Bundle: dbsched](https://github.com/padogrid/bundle-hazelcast-3n4n5-app-pado_dbsched-perf_test_dbsched-docker-mysql)

The `dbsched` bundle is preconfigured with the Pado scheduler to periodically execute jobs that dump database tables to CSV files from which it automatically extracts column information to generate the corresponding `VersionedPortable` classes. It then transforms the CSV records to objects using the generated classes before ingesting them into Hazelcast.

```console
install_bundle -download  bundle-hazelcast-3n4n5-app-pado_dbsched-perf_test_dbsched-docker-mysql
```

[![Bundle: dbsched](https://github.com/padogrid/bundle-hazelcast-3n4n5-app-pado_dbsched-perf_test_dbsched-docker-mysql/blob/master/images/db-sched.png?raw=true)](https://github.com/padogrid/bundle-hazelcast-3n4n5-app-pado_dbsched-perf_test_dbsched-docker-mysql)

---
## [4. Bundle: MySQL Sync](https://github.com/padogrid/bundle-hazelcast-3n4n5-docker-dbsync_mysql)

This bundle is preconfigured to synchronize Hazelcast with MySQL running as a Docker container. It includes the `db` cluster app to read/write from/to Hazelcast and MySQL. It also includes instructions for replacing MySQL with another database.

```bash
# Current workspace
install_bundle -download bundle-hazelcast-3n4n5-docker-dbsync_mysql

# New workspace: download 
install_bundle -download -workspace bundle-hazelcast-3n4n5-docker-dbsync_mysql

# New workspace: checkout (with Git intact)
install_bundle -checkout bundle-hazelcast-3n4n5-docker-dbsync_mysql
```

[![Bundle: MySQL Sync](https://github.com/padogrid/bundle-hazelcast-3n4n5-docker-dbsync_mysql/blob/master/images/mysql-sync.png?raw=true)](https://github.com/padogrid/bundle-hazelcast-3n4n5-docker-dbsync_mysql)

---
## [5. Debezium-Hive-Kafka Hazelcast Connector](https://github.com/padogrid/bundle-hazelcast-3n4n5-docker-debezium_hive_kafka)

This bundle integrates Hazelcast with Debezium and Apache Hive for ingesting initial data and CDC records from MySQL into a Hazelcast cluster via a Kafka sink connector included in the `padogrid` distribution. It supports inserts, updates and deletes.

```console
install_bundle -download bundle-hazelcast-3n4n5-docker-debezium_hive_kafka
```

[![Debezium-Hive-Kafka Hazelcast Connector](https://github.com/padogrid/bundle-hazelcast-3n4n5-docker-debezium_hive_kafka/blob/master/images/debezium-hive-kafka.jpg?raw=true)](https://github.com/padogrid/bundle-hazelcast-3n4n5-docker-debezium_hive_kafka)

---
## [6. Debezium-Kafka Hazelcast Connector](https://github.com/padogrid/bundle-hazelcast-3n4n5-docker-debezium_kafka)

This bundle integrates Hazelcast with Debezium for ingesting initial data and CDC records from MySQL into a Hazelcast cluster via a Kafka sink connector included in the `padogrid` distribution. It supports inserts, updates and deletes.

```console
install_bundle -download bundle-hazelcast-3n4n5-docker-debezium_kafka
```

[![Debezium-Kafka Hazelcast Connector](https://github.com/padogrid/bundle-hazelcast-3n4n5-docker-debezium_kafka/blob/master/images/debezium-kafka.png?raw=true)](https://github.com/padogrid/bundle-hazelcast-3n4n5-docker-debezium_kafka)

---
## [7. Debezium-KSQL-Kafka Hazelcast Connector](https://github.com/padogrid/bundle-hazelcast-3n4n5-docker-debezium_ksql_kafka)

This bundle integrates Hazelcast with Debezium and Confluent KSQL and ksqlDB for ingesting initial data and CDC records from MySQL into a Hazelcast cluster via a Kafka sink connector included in the `padogrid` distribution. It supports inserts, updates and deletes.

```bash
install_bundle -download bundle-hazelcast-3n4n5-docker-debezium_ksql_kafka
```

[![Debezium-KSQL-Kafka Hazelcast Connector](https://github.com/padogrid/bundle-hazelcast-3n4n5-docker-debezium_ksql_kafka/blob/master/images/debezium-ksql-kafka.jpg?raw=true)](https://github.com/padogrid/bundle-hazelcast-3n4n5-docker-debezium_ksql_kafka)

---
## [8. Hazelcast Kubernetes Helm Charts](https://github.com/padogrid/bundle-hazelcast-3n4n5-k8s-kubectl_helm)

This bundle deploys Hazelcast using Helm Charts using `kubectl`. It also includes the PadoGrid container for ingesting mock data into the Hazelcast cluster.

```bash
install_bundle -force -download bundle-hazelcast-3n4n5-k8s-kubectl_helm
```

[![Hazelcast Kubernetes Helm Charts](https://github.com/padogrid/bundle-hazelcast-3n4n5-k8s-kubectl_helm/blob/master/images/kubectl-helm.drawio.png?raw=true)](https://github.com/padogrid/bundle-hazelcast-3n4n5-k8s-kubectl_helm)

---
## [9. Hazelcast OpenShift Helm Charts](https://github.com/padogrid/bundle-hazelcast-3n4n5-k8s-oc_helm)

This bundle deploys Hazelcast using Helm Charts with Prometheus metrics enabled. It also includes the PadoGrid container for ingesting mock data into the Hazelcast cluster. For Prometheus instructions, please see the following link: [Configuring Prometheus Metrics](https://github.com/padogrid/bundle-hazelcast-3n4n5-k8s-oc_helm/blob/master/README-PROM.md).

```bash
install_bundle -download bundle-hazelcast-3n4n5-k8s-oc_helm
```

[![Hazelcast OpenShift Helm Charts](https://github.com/padogrid/bundle-hazelcast-3n4n5-k8s-oc_helm/blob/master/images/oc-helm.jpg?raw=true)](https://github.com/padogrid/bundle-hazelcast-3n4n5-k8s-oc_helm)

---
## [10. Hazelcast WAN Replication on OpenShift using Helm Charts](https://github.com/padogrid/bundle-hazelcast-3n4n5-k8s-oc_helm_wan)

This bundle demonstrates the Hazelcast WAN topology by replicating data between two (2) Hazlecast Helm Chart clusters running on OpenShift. [https://github.com/hazelcast/charts](https://github.com/hazelcast/charts)

```bash
install_bundle -download bundle-hazelcast-3n4n5-k8s-oc_helm_wan
```

[![Hazelcast WAN Replication on OpenShift using Helm Charts](https://github.com/padogrid/bundle-hazelcast-3n4n5-k8s-oc_helm_wan/blob/master/images/oc-helm-wan.jpg?raw=true)](https://github.com/padogrid/bundle-hazelcast-3n4n5-k8s-oc_helm_wan)

---
## [11. Hazelcast OpenShift Operator](https://github.com/padogrid/bundle-hazelcast-4-k8s-oc_operator)

This bundle contains OpenShift operator configuration files for deploying Hazelcast and PadoGrid. Hazelcast is deployed using the Hazelcast Operator downloaded from the `hazelcast/hazelcast-operator` repo. [https://github.com/hazelcast/hazelcast-operator](https://github.com/hazelcast/hazelcast-operator)

```bash
install_bundle -download bundle-hazelcast-4-k8s-oc_operator
```

[![Hazelcast OpenShift Operator](https://github.com/padogrid/bundle-hazelcast-4-k8s-oc_operator/blob/master/images/oc-operator.jpg?raw=true)](https://github.com/padogrid/bundle-hazelcast-4-k8s-oc_operator)

---
## [12. Hazelcast WAN Replication on OpenShift using Operator](https://github.com/padogrid/bundle-hazelcast-4-k8s-oc_operator_wan)

This bundle demonstrates the Hazelcast WAN topology by replicating data between two (2) Hazlecast Operator clusters running on OpenShift. [https://github.com/hazelcast/hazelcast-operator](https://github.com/hazelcast/hazelcast-operator)

```bash
install_bundle -download bundle-hazelcast-4-k8s-oc_operator_wan
```

[![Hazelcast WAN Replication on OpenShift using Operator](https://github.com/padogrid/bundle-hazelcast-4-k8s-oc_operator_wan/blob/master/images/oc-operator-wan.jpg?raw=true)](https://github.com/padogrid/bundle-hazelcast-4-k8s-oc_operator_wan)

---
## [13. Hazelcast Kryo/Avro Code Generator](https://github.com/padogrid/bundle-hazelcast-4n5-app-kryo_codegen)

This bundle provides step-by-step instructions for generating and deploying Avro and `KryoSerializer` in Hazelcast. Using PadoGrid's code generator, you can on the fly generate and deploy Avro wrapper classes and the correspoinding Kryo serializer.

```bash
install_bundle -download bundle-hazelcast-4n5-app-kryo_codegen
```

[![Hazelcast Kryo/Avro Code Generator](https://github.com/padogrid/bundle-hazelcast-4n5-app-kryo_codegen/blob/master/images/app-kryo-codegen.jpg?raw=true)](https://github.com/padogrid/bundle-hazelcast-4n5-app-kryo_codegen)

---
## [14. Cluster Split-Brain](https://github.com/padogrid/bundle-hazelcast-4n5-app-perf_test_sb-cluster-sb)

This bundle provides scripts, configuration files, and apps for creating a Hazelcast 4.x network split-brain environment where you can test Hazelcast's split-brain capabilities.

```console
install_bundle -download bundle-hazelcast-4n5-app-perf_test_sb-cluster-sb
```

[![Cluster Split-Brain](https://github.com/padogrid/bundle-hazelcast-4n5-app-perf_test_sb-cluster-sb/blob/master/images/split-brain.png?raw=true)](https://github.com/padogrid/bundle-hazelcast-4n5-app-perf_test_sb-cluster-sb)

---
## [15. Session Expiration Management Plugin](https://github.com/padogrid/bundle-hazelcast-4n5-cluster-session)

This bundle provides a plugin that expires session objects in a given map and their relevant entries in other Hazelcast maps. The plugin also supports session expirations over the WAN (See [bundle-hazelcast-4n5-cluster-session-wan](https://github.com/padogrid/bundle-hazelcast-4n5-cluster-session-wan).)

```bash
install_bundle -download bundle-hazelcast-4n5-cluster-session
```

[![Session Expiration Management Plugin](https://github.com/padogrid/bundle-hazelcast-4n5-cluster-session/blob/master/images/session.jpg?raw=true)](https://github.com/padogrid/bundle-hazelcast-4n5-cluster-session)

---
## [16. Session Expiration in WAN Environment](https://github.com/padogrid/bundle-hazelcast-4n5-cluster-session-wan)

This bundle demonstrates the session expiration plugin in a WAN environment. It incorporates the session expiration plugin included in [bundle-hazelcast-4n5-cluster-session](https://github.com/padogrid/bundle-hazelcast-4n5-cluster-session.git) and Sorint.lab's `IpDiscoveryStrategy` plugin.

```bash
# To run
install_bundle -download -workspace bundle-hazelcast-4n5-cluster-session-wan

# To run and/or check in
install_bundle -checkout bundle-hazelcast-4n5-cluster-session-wan
```
```bash
# If behind firewall, then manually download the bundle distribution and execute the following.
install_bundle -workspace session-wan bundle-hazelcast-4n5-cluster-session-wan-master.zip
switch_workspace sesson-wan
```

[![Session Expiration in WAN Environment](https://github.com/padogrid/bundle-hazelcast-4n5-cluster-session-wan/blob/master/images/wan-session-expiration.png?raw=true)](https://github.com/padogrid/bundle-hazelcast-4n5-cluster-session-wan)

---
## [17. Neural Network: LSTM RNN](https://github.com/padogrid/bundle-hazelcast-5-app-ml_lstm-cluster-ml_jet)

This bundle demonstrates forecasting future events in real time using LSTM RNN (Long Short-Term Memory Recurrent Neural Network) via Keras backed by TensorFlow. It constructs a Hazelcast Jet pipeline to apply LSTM RNN models on streamed data.

```bash
# --- Execute one of the following install_bundle commands:

# Download and install as a workspace
install_bundle -download -workspace bundle-hazelcast-5-app-ml_lstm-cluster-ml_jet

# Specify '-init' to automatically build the bundle environment.
# This requires Java 11 executable in your path.
install_bundle -init -checkout bundle-hazelcast-5-app-ml_lstm-cluster-ml_jet
```

[![Neural Network: LSTM RNN](https://github.com/padogrid/bundle-hazelcast-5-app-ml_lstm-cluster-ml_jet/blob/master/images/ml-lstm-dna.drawio.png?raw=true)](https://github.com/padogrid/bundle-hazelcast-5-app-ml_lstm-cluster-ml_jet)

---
## [18. Hazelcast Multi-Cluster Demo](https://github.com/padogrid/bundle-hazelcast-5-cluster-wan-app-grafana)

This bundle demonstrates Grafana capabilities of monitoring five (5) Hazelcast clusters. It includes three (3) independent clusters and two (2) bi-directional WAN clusters along with a workflow simulator.

```bash
install_bundle -init -download -workspace bundle-hazelcast-5-cluster-wan-app-grafana
```

[![Hazelcast Multi-Cluster Demo](https://github.com/padogrid/bundle-hazelcast-5-cluster-wan-app-grafana/blob/master/images/multi-clusters.drawio.png?raw=true)](https://github.com/padogrid/bundle-hazelcast-5-cluster-wan-app-grafana)

---
## [19. Debezium-ksqlDB-Confluent Hazelcast Connector](https://github.com/padogrid/bundle-hazelcast-5-docker-debezium_ksqldb_confluent)

This bundle integrates Hazelcast with Debezium and Confluent ksqlDB for ingesting initial data and CDC records from MySQL into Kafka and Hazelcast via a Kafka sink connector included in the `padogrid` distribution.

```bash
install_bundle -download -workspace bundle-hazelcast-5-docker-debezium_ksqldb_confluent
```

[![Debezium-ksqlDB-Confluent Hazelcast Connector](https://github.com/padogrid/bundle-hazelcast-5-docker-debezium_ksqldb_confluent/blob/master/images/hazelcast-debezium-confluent.png?raw=true)](https://github.com/padogrid/bundle-hazelcast-5-docker-debezium_ksqldb_confluent)

---
## [20. Hazelcast Kubernetes Operator](https://github.com/padogrid/bundle-hazelcast-5-k8s-hz_operator)

This bundle provides step-by-step instructions for deploying and testing Hazelcast Platform Operator, Hazelcast, and PadoGrid. ![Hazelcast Platform Operator](images/hz-operator-helm.drawio.png)

```bash
install_bundle -download bundle-hazelcast-5-k8s-operator
```

[![Hazelcast Kubernetes Operator](https://github.com/padogrid/bundle-hazelcast-5-k8s-hz_operator/blob/master/images/hz-operator-helm.drawio.png?raw=true)](https://github.com/padogrid/bundle-hazelcast-5-k8s-hz_operator)

---
## [21. PadoGrid Hazelcast Playground](https://github.com/padogrid/bundle-hazelcast-5-playground-python)

This bundle includes Hazelcast Playground, a web app for browsing and updating Hazelcast data structures.

```bash
install_bundle -download bundle-hazelcast-5-playground-python
```

[![PadoGrid Hazelcast Playground](https://github.com/padogrid/bundle-hazelcast-5-playground-python/blob/master/images/playground-screenshot.png?raw=true)](https://github.com/padogrid/bundle-hazelcast-5-playground-python)

---
## [22. Hazelcast Job: Executing Remote Python Code ](https://github.com/padogrid/bundle-hazelcast-5-tutorial-app-jet_python)

This bundle walks through the Hazelcast Jet job preparation, submission, and deubgging steps in detail and provides troubleshooting tips.

```bash
install_bundle -download bundle-hazelcast-5-tutorial-app-jet_python
```

[![Hazelcast Job: Executing Remote Python Code ](https://github.com/padogrid/bundle-hazelcast-5-tutorial-app-jet_python/blob/master/images/jet_python.drawio.png?raw=true)](https://github.com/padogrid/bundle-hazelcast-5-tutorial-app-jet_python)

---
## [23. Hazelcast JupyterLab Python Examples](https://github.com/padogrid/bundle-hazelcast-examples-python)

This bundle provides Hazelcast Python client examples running on JupyterLab in PadoGrid. It demonstrates how PadoGrid workspaces are seamlessly integrated with JupyterLab workspaces.

```bash
install_bundle -download -workspace bundle-hazelcast-examples-python
```

[![Hazelcast JupyterLab Python Examples](https://github.com/padogrid/bundle-hazelcast-examples-python/blob/master/images/examples-python.drawio.png?raw=true)](https://github.com/padogrid/bundle-hazelcast-examples-python)

---
## [24. Hazelcast Bundle Template](https://github.com/padogrid/bundle-hazelcast-template)

This bundle serves as a template for creating a new Hazelcast onlne bundle.

```bash
install_bundle -download bundle-hazelcast-template
```

[![Hazelcast Bundle Template](https://github.com/padogrid/padogrid/wiki/Quick-Start)](https://github.com/padogrid/bundle-hazelcast-template)

---
## [25. Rolling Upgrade Training](https://github.com/padogrid/bundle-hazelcast-training-3.11-app-perf_test_v3.11-cluster-v3.11)

As part of the Rolling Upgrade lab of Hazelcast Operations Training, this bundle includes a cluster and an app preconfigured to run with Hazelcast Enterprise 3.11.x which must be installed separately.

```bash
install_bundle -download bundle-hazelcast-training-3.11-app-perf_test_v3.11-cluster-v3.11
```

[![Rolling Upgrade Training](https://github.com/padogrid/padogrid/wiki/Quick-Start)](https://github.com/padogrid/bundle-hazelcast-training-3.11-app-perf_test_v3.11-cluster-v3.11)

---
## [26. IMDG Cluster: openssl](https://github.com/padogrid/bundle-hazelcast-training-3n4n5-app-perf_test_openssl-cluster-openssl)

As part of the TLS/SSL lab of Hazelcast Operations Training, this bundle includes the `openssl` cluster preconfigured to enable OpenSSL/BoringSSL.

```bash
install_bundle -download bundle-hazelcast-training-3n4n5-app-perf_test_openssl-cluster-openssl
```

[![IMDG Cluster: openssl](https://github.com/padogrid/bundle-hazelcast-training-3n4n5-app-perf_test_openssl-cluster-openssl/blob/master/images/openssl-cluster.jpg?raw=true)](https://github.com/padogrid/bundle-hazelcast-training-3n4n5-app-perf_test_openssl-cluster-openssl)

---
## [27. IMDG Cluster: ssl](https://github.com/padogrid/bundle-hazelcast-training-3n4n5-app-perf_test_ssl-cluster-ssl)

As part of the TLS/SSL lab of Hazelcast Operations Training, the `ssl` cluster has been preconfigured to enable SSL. It contains scripts to create both private and trust keystores that contain both member and client keys and certificates.

```bash
install_bundle -download bundle-hazelcast-training-3n4n5-app-perf_test_ssl-cluster-ssl
```

[![IMDG Cluster: ssl](https://github.com/padogrid/bundle-hazelcast-training-3n4n5-app-perf_test_ssl-cluster-ssl/blob/master/images/ssl-cluster.jpg?raw=true)](https://github.com/padogrid/bundle-hazelcast-training-3n4n5-app-perf_test_ssl-cluster-ssl)

---

# :books: Kafka Bundle Catalog :books:

The online bundles can be installed by executing the `install_bundle` commands as shown below. To view use case details for each bundle, click on their image.

*The bundles listed below are sorted by bundle names, and as such the order of bundles may change as new bundles are introduced.*

---
## [1. Kafka Bundle Template](https://github.com/padogrid/bundle-kafka-template)

This bundle serves as a template for creating a new Kafka onlne bundle.

```bash
install_bundle -download bundle-kafka-template
```

[![Kafka Bundle Template](https://github.com/padogrid/padogrid/wiki/Quick-Start)](https://github.com/padogrid/bundle-kafka-template)

---

# :books: Kafka Confluent Bundle Catalog :books:

The online bundles can be installed by executing the `install_bundle` commands as shown below. To view use case details for each bundle, click on their image.

*The bundles listed below are sorted by bundle names, and as such the order of bundles may change as new bundles are introduced.*

---
## [1. Confluent JupyterLab Python Examples](https://github.com/padogrid/bundle-confluent-7-examples-python)

This bundle provides Kafka Python client examples running on JupyterLab in PadoGrid. It demonstrates how PadoGrid workspaces are seamlessly integrated with JupyterLab workspaces.

```bash
install_bundle -download -workspace bundle-confluent-7-examples-python
```

[![Confluent JupyterLab Python Examples](https://github.com/padogrid/bundle-confluent-7-examples-python/blob/master/images/confluent-examples-python.drawio.png?raw=true)](https://github.com/padogrid/bundle-confluent-7-examples-python)

---
## [2. Kafka Confluent Bundle Template](https://github.com/padogrid/bundle-confluent-template)

This bundle serves as a template for creating a new Kafka onlne bundle.

```bash
install_bundle -download bundle-confluent-template
```

[![Kafka Confluent Bundle Template](https://github.com/padogrid/padogrid/wiki/Quick-Start)](https://github.com/padogrid/bundle-confluent-template)

---

# :books: Mosquitto Bundle Catalog :books:

The online bundles can be installed by executing the `install_bundle` commands as shown below. To view use case details for each bundle, click on their image.

*The bundles listed below are sorted by bundle names, and as such the order of bundles may change as new bundles are introduced.*

---
## [1. Mosquitto/MQTT Bundle Template](https://github.com/padogrid/bundle-mosquitto-template)

This bundle serves as a template for creating a new Mosquitto/MQTT onlne bundle.

```bash
install_bundle -download bundle-mosquitto-template
```

[![Mosquitto/MQTT Bundle Template](https://github.com/padogrid/padogrid/wiki/Quick-Start)](https://github.com/padogrid/bundle-mosquitto-template)

---
## [2. Mosquitto/MQTT Virtual Cluster Tutorial](https://github.com/padogrid/bundle-mosquitto-tutorial-virtual-clusters)

This bundle provides a hands-on tutorial demonstrating PadoGrid's virtual cluster capabilities.

```bash
install_bundle -download -workspace bundle-mosquitto-tutorial-virtual-clusters
```

[![Mosquitto/MQTT Virtual Cluster Tutorial](https://github.com/padogrid/bundle-mosquitto-tutorial-virtual-clusters/blob/master/images/mqtt-mosquitto-tutorial.drawio.png?raw=true)](https://github.com/padogrid/bundle-mosquitto-tutorial-virtual-clusters)

---

# :books: SnappyData/ConputeDB Bundle Catalog :books:

The online bundles can be installed by executing the `install_bundle` commands as shown below. To view use case details for each bundle, click on their image.

*The bundles listed below are sorted by bundle names, and as such the order of bundles may change as new bundles are introduced.*

---
## [1. Debezium-Kafka SnappyData/ComputeDB Connector](https://github.com/padogrid/bundle-snappydata-1-docker-debezium_kafka)

This bundle integrates SnappyData/ComputeDB with Debezium for ingesting initial data and CDC records from MySQL into a SnappyData/ComputeDB cluster via a Kafka sink connector included in the `padogrid` distribution. It supports inserts, updates and deletes.

```console
install_bundle -download bundle-snappydata-1-docker-debezium_kafka
```

[![Debezium-Kafka SnappyData/ComputeDB Connector](https://github.com/padogrid/bundle-snappydata-1-docker-debezium_kafka/blob/master/images/debezium-kafka.jpg?raw=true)](https://github.com/padogrid/bundle-snappydata-1-docker-debezium_kafka)

---
## [2. SnappyData Bundle Template](https://github.com/padogrid/bundle-snappydata-template)

This bundle serves as a template for creating a new SnappyData onlne bundle.

```bash
install_bundle -download bundle-snappydata-template
```

[![SnappyData Bundle Template](https://github.com/padogrid/padogrid/wiki/Quick-Start)](https://github.com/padogrid/bundle-snappydata-template)

---

# :books: Coherence Bundle Catalog :books:

The online bundles can be installed by executing the `install_bundle` commands as shown below. To view use case details for each bundle, click on their image.

*The bundles listed below are sorted by bundle names, and as such the order of bundles may change as new bundles are introduced.*

---
## [1. Coherence Bundle Template](https://github.com/padogrid/bundle-coherence-template)

This bundle serves as a template for creating a new Coherence onlne bundle.

```bash
install_bundle -download bundle-coherence-template
```

[![Coherence Bundle Template](https://github.com/padogrid/padogrid/wiki/Quick-Start)](https://github.com/padogrid/bundle-coherence-template)

---

![PadoGrid](https://github.com/padogrid/padogrid/raw/develop/images/padogrid-3d-16x16.png) [*PadoGrid*](https://github.com/padogrid) | [*Catalogs*](https://github.com/padogrid/catalog-bundles/blob/master/all-catalog.md) | [*Manual*](https://github.com/padogrid/padogrid/wiki) | [*FAQ*](https://github.com/padogrid/padogrid/wiki/faq) | [*Releases*](https://github.com/padogrid/padogrid/releases) | [*Templates*](https://github.com/padogrid/padogrid/wiki/Using-Bundle-Templates) | [*Pods*](https://github.com/padogrid/padogrid/wiki/Understanding-Padogrid-Pods) | [*Kubernetes*](https://github.com/padogrid/padogrid/wiki/Kubernetes) | [*Docker*](https://github.com/padogrid/padogrid/wiki/Docker) | [*Apps*](https://github.com/padogrid/padogrid/wiki/Apps) | [*Quick Start*](https://github.com/padogrid/padogrid/wiki/Quick-Start)
