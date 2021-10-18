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
## 3. Debezium-Hive-Kafka Hazelcast Connector

This bundle integrates Hazelcast with Debezium and Apache Hive for ingesting initial data and CDC records from MySQL into a Hazelcast cluster via a Kafka sink connector included in the `padogrid` distribution. It supports inserts, updates and deletes.

```bash
install_bundle -download bundle-hazelcast-3n4-docker-debezium_hive_kafka
```

[![Debezium-Hive-Kafka Hazelcast Connector](https://github.com/padogrid/bundle-hazelcast-3n4-docker-debezium_hive_kafka/blob/master/images/debezium-hive-kafka.jpg?raw=true)](https://github.com/padogrid/bundle-hazelcast-3n4-docker-debezium_hive_kafka)

---
## 4. Debezium-Kafka Hazelcast Connector

This bundle integrates Hazelcast with Debezium for ingesting initial data and CDC records from MySQL into a Hazelcast cluster via a Kafka sink connector included in the `padogrid` distribution. It supports inserts, updates and deletes.

```bash
install_bundle -download bundle-hazelcast-3n4-docker-debezium_kafka
```

[![Debezium-Kafka Hazelcast Connector](https://github.com/padogrid/bundle-hazelcast-3n4-docker-debezium_kafka/blob/master//images/debezium-kafka.png?raw=true)](https://github.com/padogrid/bundle-hazelcast-3n4-docker-debezium_kafka)

---
## 5. App: Pado

The pado app provides a Hazelcast `Portable` class generator and CSV file import tools for Hazelcast. This bundle includes step-by-step instructions for ingesting mock data and UCI Machine Learning datasets into Hazelcast. It also includes a Pado scheduler demo that automates scheduled job executions for exporting and importing data from databases.

```bash
install_bundle -download bundle-hazelcast-3n4n5-app-pado
```

[![App: Pado](https://github.com/padogrid/bundle-hazelcast-3n4n5-app-pado/blob/master/images/app-pado-import.png?raw=true)](https://github.com/padogrid/bundle-hazelcast-3n4n5-app-pado)

---
## 6. Bundle: MySQL Sync

This bundle is preconfigured to synchronize Hazelcast with MySQL running as a Docker container. It includes the `db` cluster app to read/write from/to Hazelcast and MySQL. It also includes instructions for replacing MySQL with another database.

```bash
install_bundle -download bundle-hazelcast-3n4n5-docker-dbsync_mysql
```

[![Bundle: MySQL Sync](https://github.com/padogrid/bundle-hazelcast-3n4n5-docker-dbsync_mysql/blob/master/images/mysql-sync.png?raw=true)](https://github.com/padogrid/bundle-hazelcast-3n4n5-docker-dbsync_mysql)

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
install_bundle -download bundle-hazelcast-4-k8s-oc_helm
```

[![Hazelcast OpenShift Helm Charts](https://github.com/padogrid/bundle-hazelcast-4-k8s-oc_helm/blob/master/images/oc-helm.jpg?raw=true)](https://github.com/padogrid/bundle-hazelcast-4-k8s-oc_helm)

---
## 9. Hazelcast WAN Replication on OpenShift using Helm Charts

This bundle demonstrates the Hazelcast WAN topology by replicating data between two (2) Hazlecast Helm Chart clusters running on OpenShift.

```bash
install_bundle -download bundle-hazelcast-4-k8s-oc_helm_wan
```

[![Hazelcast WAN Replication on OpenShift using Helm Charts](https://github.com/padogrid/bundle-hazelcast-4-k8s-oc_helm_wan/blob/master/images/oc-helm-wan.jpg?raw=true)](https://github.com/padogrid/bundle-hazelcast-4-k8s-oc_helm_wan)

---
## 10. Hazelcast OpenShift Operator

This bundle contains OpenShift operator configuration files for deploying Hazelcast and PadoGrid. Hazelcast is deployed using the Hazelcast Operator downloaded from the 'hazelcast/hazelcast-operator' repo.

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
## 14. Hazelcast Bundle Template

This bundle serves as a template for creating a new Hazelcast onlne bundle.

```bash
install_bundle -download bundle-hazelcast-template
```

[![Hazelcast Bundle Template](https://github.com/padogrid/bundle-hazelcast-template/blob/master/?raw=true)](https://github.com/padogrid/bundle-hazelcast-template)

---
## 15. Rolling Upgrade Training

As part of the Rolling Upgrade lab of Hazelcast Operations Training, this bundle includes a cluster and an app preconfigured to run with Hazelcast Enterprise 3.11.x which must be installed separately.

```bash
install_bundle -download bundle-hazelcast-training-3.11-app-perf_test_v3.11-cluster-v3.11
```

[![Rolling Upgrade Training](https://github.com/padogrid/bundle-hazelcast-training-3.11-app-perf_test_v3.11-cluster-v3.11/blob/master/?raw=true)](https://github.com/padogrid/bundle-hazelcast-training-3.11-app-perf_test_v3.11-cluster-v3.11)

---
## 16. IMDG Cluster: openssl

As part of the TLS/SSL lab of Hazelcast Operations Training, this bundle includes the `openssl` cluster preconfigured to enable OpenSSL/BoringSSL.

```bash
install_bundle -download bundle-hazelcast-training-3n4n5-app-perf_test_openssl-cluster-openssl
```

[![IMDG Cluster: openssl](https://github.com/padogrid/bundle-hazelcast-training-3n4n5-app-perf_test_openssl-cluster-openssl/blob/master/images/openssl-cluster.jpg?raw=true)](https://github.com/padogrid/bundle-hazelcast-training-3n4n5-app-perf_test_openssl-cluster-openssl)

---
## 17. IMDG Cluster: ssl

As part of the TLS/SSL lab of Hazelcast Operations Training, the `ssl` cluster has been preconfigured to enable SSL. It contains scripts to create both private and trust keystores that contain both member and client keys and certificates.

```bash
install_bundle -download bundle-hazelcast-training-3n4n5-app-perf_test_ssl-cluster-ssl
```

[![IMDG Cluster: ssl](https://github.com/padogrid/bundle-hazelcast-training-3n4n5-app-perf_test_ssl-cluster-ssl/blob/master/images/ssl-cluster.jpg?raw=true)](https://github.com/padogrid/bundle-hazelcast-training-3n4n5-app-perf_test_ssl-cluster-ssl)
