FROM java
MAINTAINER Codex Digital
EXPOSE 7474
EXPOSE 7687
EXPOSE 1337
WORKDIR /
RUN ulimit -n 65536
ADD neo4j /var/lib/neo4j
CMD /var/lib/neo4j/bin/neo4j console
