FROM openjdk:latest
RUN mkdir -p /apps/svr
COPY test.class /apps/svr/
COPY sh.sh /apps/svr/
ENV GOPATH /apps
ENV PYTHONPATH /mnt
CMD ["sh", "/apps/svr/sh.sh"]
