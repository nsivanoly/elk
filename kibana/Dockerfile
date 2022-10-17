ARG ELASTIC_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/kibana/kibana:${ELASTIC_VERSION}

# Add your kibana plugins setup here
# Example: RUN kibana-plugin install <name|url>
RUN kibana-plugin install https://github.com/fbaligand/kibana-enhanced-table/releases/download/v1.13.3/enhanced-table-1.13.3_8.4.3.zip
