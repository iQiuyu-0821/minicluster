# Minicluster

An application to run a minicluster of HDFS, Hive or Hive2 for testing purposes.

## Docker

Simply build the docker container using

```bash
build --no-cache -t minicluster .
```

For a Hive cluster, run:

```bash
docker run minicluster hive
```

For a HDFS cluster, run:

```bash
docker run minicluster hdfs
```