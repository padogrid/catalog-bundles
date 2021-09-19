# Building catalogs

This rep includes two (2) scripts for building catalogs. To build catalogs for all products, run `update_all_catalog`. To build a catalog for a single product, run `update_catalog` as shown in examples below.

Build all catalogs. Typically, this command is used to update all in one shot.

```bash
./update_all_catalogs
```

Build one catalog at a time.

```bash
# Build geode catalog
./update_catalog -product geode

# Build hazelcast catalog
./update_catalog -product hazelcast

# See the usage
./update_catalog -?
```

Once the catalogs are built (or updated), check in the updated files.

```bash
git commit -a -m "Updated ..."
git push
```
