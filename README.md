# playGobblin
Apache Gobblin in Practice

Job Configuration Basics
https://gobblin.readthedocs.io/en/latest/user-guide/Working-with-Job-Configuration-Files/
 
Kafka-HDFS Ingestion
https://gobblin.readthedocs.io/en/latest/case-studies/Kafka-HDFS-Ingestion/

gobblin-modules source
https://www.javatips.net/api/gobblin-master/gobblin-modules/gobblin-kafka-09/src/main/java/gobblin/source/extractor/extract/kafka/KafkaSimpleStreamingExtractor.java

### [Docker Integration](https://gobblin.readthedocs.io/en/latest/user-guide/Docker-Integration/)
#### [Gobblin Wikipedia Repo](https://gobblin.readthedocs.io/en/latest/user-guide/Docker-Integration/#gobblin-wikipedia-repository)
```
docker run --name gobblin --rm -v /Users/phu021/gobblin/workdir:/home/gobblin/work-dir gobblin/gobblin-wikipedia:ubuntu-gobblin-latest
```

###[Gobblin Standalone]()
```
docker run  --name gobblin --rm  -v /Users/{}/gobblin/conf:/etc/opt/job-conf   -v /Users/{}/gobblin/workdir:/home/gobblin/work-dir   -v /Users/{}/gobblin/logs:/var/log/gobblin    gobblin/gobblin-standalone:ubuntu-gobblin-latest
```
