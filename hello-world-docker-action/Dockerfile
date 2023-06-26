# Container image that runs your code
FROM alpine:3.10
COPY entrypoint.sh /entrypoint.sh
RUN chmod +X /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]
