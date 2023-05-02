ARG ELASTIC_VERSION

FROM docker.elastic.co/elasticsearch/elasticsearch:${ELASTIC_VERSION}

COPY ./alerting.zip /opendistro/alerting.zip
RUN bin/elasticsearch-plugin install -b file:///opendistro/alerting.zip
