Easy to play with in a running SonarQube. Add to `conf/sonar.properties`:

    sonar.search.httpPort = 9200

Random examples:

    curl localhost:9200/_search
    curl localhost:9200/issues
    curl localhost:9200/issues/_search
    /_cat
    /_cat/health?v
    curl localhost:9200/_cat/indices?v
    curl localhost:9200/customer?pretty -XPUT
