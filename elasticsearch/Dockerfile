# https://github.com/elastic/elasticsearch-docker
#FROM elasticsearch:5.5.2-alpine5.5.2
FROM docker.elastic.co/elasticsearch/elasticsearch:6.3.0

# Add your elasticsearch plugins setup here
# Example: RUN elasticsearch-plugin install analysis-icu
# RUN elasticsearch-plugin install x-pack
RUN elasticsearch-plugin install https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v6.3.0/elasticsearch-analysis-ik-6.3.0.zip
# ADD x-pack/x-pack-5.5.2.jar /usr/share/elasticsearch/plugins/x-pack/x-pack-5.5.2.jar
