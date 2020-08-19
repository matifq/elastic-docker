# Elastic-Docker (single node)


## References @compose file
- https://www.elastic.co/guide/en/elasticsearch/reference/current/docker.html
- https://stackoverflow.com/questions/52373356/docker-bind-elasticsearch-volume-in-app-folder
- https://medium.com/@TimvanBaarsen/how-to-run-an-elasticsearch-7-x-single-node-cluster-for-local-development-using-docker-compose-2b7ab73d8b82

## Run Docker
```sh
$ docker-compose up
```

## Verify the deployment by navigating in your preferred browser.

```sh
http://localhost:9200/
```

## Data folder
- elasticsearch-data/
