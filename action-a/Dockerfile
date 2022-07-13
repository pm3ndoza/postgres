FROM debian:9.5-slim

ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
RUN ls -lsa
ENTRYPOINT ["/entrypoint.sh"]
