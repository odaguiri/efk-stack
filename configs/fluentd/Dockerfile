FROM fluent/fluentd:v0.12-debian
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-rdoc", "--no-ri", "--version", "1.9.2"]
RUN ["gem", "install", "fluent-plugin-json-parser", "--no-rdoc", "--no-ri"]
RUN ["gem", "install", "fluent-plugin-geoip", "--no-rdoc", "--no-ri"]
