## Elasticsearch, Head, Kibana, Marvel and Sense in one container

Simple and lightweight docker image for previewing Elasticsearch, Head, Kibana, Marvel and Sense.

### Usage

    docker run -d -p 9200:9200 -p 5601:5601 arcseldon/elasticsearch-head-kibana-marvel-sense

You can connect to Elasticsearch with `http://localhost:9200` and its Kibana front-end with `http://localhost:5601`.

You can connect to Marvel with `http://localhost:5601/app/marvel` and Sense with `http://localhost:5601/app/sense`

Finally, you can connect to Head with `http://localhost:9200/_plugin/head/`
 

### Tags

* latest

    Elasticsearch Head Kibana Marvel Sense

### Tips

* To install plugins just view the Dockerfile and copy a line similar to your needs and modify as needed 

* To build the image using the Dockerfile just use eg. `docker build -t arcseldon/elasticsearch-head-kibana-marvel-sense .`



