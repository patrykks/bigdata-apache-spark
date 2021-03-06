# Apache Spark tutorial

## Docker images

### Part 1 GraphX

`docker pull dylanmei/zeppelin`

### Part 2 Mazerunner

`docker pull sequenceiq/hadoop-docker:2.4.1`

`docker pull kbastani/spark-neo4j:latest`

`docker pull kbastani/neo4j-graph-analytics:latest`

`docker pull kbastani/docker-neo4j:latest`

--

## Tutorials

### Part 1 GraphX

1. Clone the repository: `git clone https://github.com/patrykks/bigdata-apache-spark.git`
2. `cd bigdata-apache-spark`
3. Run with Docker Compose: `docker-compose up`
4. Your Zeppelin notepad will be running at `localhost:8080`

### Part 2 Mazerunner
1. run

 1. Linux: `sudo docker run  -v /var/run/docker.sock:/var/run/docker.sock \-ti kbastani/spark-neo4j up -d`

 2. Windows: `docker run -v /var/run/docker.sock:/var/run/docker.sock -ti kbastani/spark-neo4j up -d`

2. Your neo4j will be running at `localhost:7474/browser`
