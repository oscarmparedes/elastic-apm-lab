FROM docker.elastic.co/beats/metricbeat:7.12.1
COPY metricbeat.yml /usr/share/metricbeat/metricbeat.yml
USER root
RUN chown -R root:metricbeat /usr/share/metricbeat/
RUN chmod go-w /usr/share/metricbeat/metricbeat.yml

#RUN export PATH=$PATH:/usr/share/metricbeat/bin
USER metricbeat