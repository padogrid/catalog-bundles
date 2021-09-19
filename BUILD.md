# Building catalogs

This repo includes two (2) scripts for building catalogs. To build catalogs for all products, run `update_all_catalog`. To build a catalog for a single product, run `update_catalog` as shown in the examples below.

To avoid staled catalogs, it is important that you update the catalogs  whenenver any of the following events occur.

- Added a new bundle
- Renamed a bundle repo
- Updated the bundle header description

## Build All Catalogs

Build all catalogs. Typically, this command is used to update all the catalogs in one shot.

```bash
./update_all_catalogs
```

## Build Individual Catalog

Optionally, build one catalog at a time.

```bash
# Build geode catalog
./update_catalog -product geode

# Build hazelcast catalog
./update_catalog -product hazelcast

# See the usage
./update_catalog -?
```

## Check-in

Once the catalogs are built (or updated), check in the updated files.

```bash
git commit -a -m "Updated ..."
git push
```
