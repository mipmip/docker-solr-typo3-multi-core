# Apache Solr for TYPO3 CMS DOCKER CUSTOMIZED FOR LINGEWOUD

This docker is a customized version from https://github.com/TYPO3-Solr/ext-solr


```
docker build -t mipmip/docker-solr-typo3-multi-core .


docker run -d -p 127.0.0.1:8983:8983 -v "$PWD/solr-conf-data:/opt/solr/server/solr/" .
```



