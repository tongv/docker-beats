FROM docker.elastic.co/beats/filebeat:6.1.0
USER root
RUN cd /usr/share/filebeat/kibana/default/dashboard &&\
    rm -f *apache2* *Postgresql* *traefik* 
