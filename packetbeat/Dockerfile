FROM docker.elastic.co/beats/packetbeat:6.1.0
USER root
RUN cd /usr/share/packetbeat/kibana/default/dashboard &&\
    rm -f *thrift* *pgsql* *cassandra* 
