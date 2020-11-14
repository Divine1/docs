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


/usr/share/logstash/config/logstash.yml
http.host: "0.0.0.0"
xpack.monitoring.elasticsearch.hosts: [ "http://167.71.173.154:9200" ]


/usr/share/logstash/pipeline/logstash.conf

docker run -d -p 9600:9600 -p 5044:5044 -v /root/logstashfiles/logstash.yml:/usr/share/logstash/config/logstash.yml -v /root/logstashfiles/logstash.conf:/usr/share/logstash/pipeline/logstash.conf cc67e625d974


docker run -d -p 9600:9600 -p 5044:5044 -v /home/elkuser/elkstack/softwares/logstash_file_docker/logstash.yml:/usr/share/logstash/config/logstash.yml -v /home/elkuser/elkstack/softwares/logstash_file_docker/pipeline-final.conf:/usr/share/logstash/pipeline/logstash.conf cc67e625d974



```
