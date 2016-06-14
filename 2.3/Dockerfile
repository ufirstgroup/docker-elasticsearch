FROM elasticsearch:2.3

RUN plugin install license \
 && plugin install marvel-agent \
 && plugin install mobz/elasticsearch-head \
 && plugin install lmenezes/elasticsearch-kopf/v2.1.2 \
 && plugin install delete-by-query \
 && plugin install elasticsearch/elasticsearch-analysis-icu/2.7.0
