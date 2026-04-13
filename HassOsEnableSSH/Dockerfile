ARG BUILD_FROM=hassioaddons/base:8.0.6
FROM $BUILD_FROM
ENV LANG C.UTF-8
COPY run.sh /
WORKDIR /data
RUN chmod a+x /run.sh

CMD [ "/run.sh" ]
