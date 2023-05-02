ARG ELASTIC_VERSION

FROM docker.elastic.co/kibana/kibana:${ELASTIC_VERSION}

COPY ./opendistroAlertingKibana-1.13.0.0.zip /opendistro/opendistroAlertingKibana-1.13.0.0.zip

RUN bin/kibana-plugin install file:///opendistro/opendistroAlertingKibana-1.13.0.0.zip
