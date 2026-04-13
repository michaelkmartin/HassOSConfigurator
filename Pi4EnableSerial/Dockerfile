ARG BUILD_FROM=docker pull ghcr.io/hassio-addons/base:16.2.1
FROM $BUILD_FROM
ENV LANG C.UTF-8
COPY run.sh /
WORKDIR /data
RUN chmod a+x /run.sh

CMD [ "/run.sh" ]
