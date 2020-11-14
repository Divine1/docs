```
https://docs.docker.com/engine/install/ubuntu/
https://www.docker.elastic.co/r/logstash/logstash:7.8.1

docker pull docker.elastic.co/logstash/logstash:7.8.1

/usr/share/logstash/pipeline/logstash.conf


docker run -d -v $PWD/db:/data/db -p 8080:80 imageid


docker run -d -v $PWD/db:/data/db -p 9600:9600 -p 5044:5044 imageid

docker run -d -v $PWD:/usr/share/logstash/pipeline -p 9600:9600 -p 5044:5044 imageid

docker run -d -p 9600:9600 -p 5044:5044 -v $PWD:/usr/share/logstash/pipeline cc67e

docker run -d -p 9600:9600 -p 5044:5044 cc67e

docker run -d -v $PWD:/usr/share/logstash/pipeline cc67e

docker run -v /root:/usr/share/logstash/pipeline cc67e

docker exec -it containerid bash


input { 
  beats { 
    port => 5044 
  }
}
output {
  stdout { codec => rubydebug }
}

```
