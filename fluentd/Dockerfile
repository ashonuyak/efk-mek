# fluentd/Dockerfile
FROM fluent/fluentd:v0.12-debian
RUN gem install representable -v 3.0.4 \
  && gem install faraday -v 0.17.4 \
  && gem install fluent-plugin-elasticsearch --no-rdoc --no-ri --version 1.9.2