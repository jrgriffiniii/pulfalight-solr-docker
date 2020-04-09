# Docker for Pulfalight Solr

This is a [Docker](https://docker.com) image used for testing with [PULFALight](https://github.com/pulibrary/pulfalight) with the latest releases of [Apache Solr](https://lucene.apache.org/solr/).

## Building the Image
```bash
docker build -t pulfalight-solr .
```

## Updating the Image
```bash
docker tag pulfalight-solr pulibrary/pulfalight-solr:1.0.x
docker tag pulfalight-solr pulibrary/pulfalight-solr:latest
docker push pulibrary/pulfalight-solr
```
