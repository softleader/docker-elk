# https://github.com/elastic/logstash-docker
# https://www.elastic.co/guide/en/logstash/current/_pulling_the_image.html
FROM docker.elastic.co/logstash/logstash:5.6.0

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json

COPY config/logstash.yml /usr/share/logstash/config/logstash.yml