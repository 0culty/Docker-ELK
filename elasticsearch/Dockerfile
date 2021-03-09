ARG ELK_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/elasticsearch/elasticsearch:${ELK_VERSION}

# 한글 분석기 nori 설치
RUN elasticsearch-plugin install analysis-nori