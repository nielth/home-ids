FROM opensearchproject/logstash-oss-with-opensearch-output-plugin:8.4.0
COPY --chown=logstash:root logstash.conf /usr/share/logstash/pipeline/logstash.conf
COPY --chown=logstash:root suricata_template.json /etc/logstash/templates/suricata_template.json
