ARG BUILD_FROM
FROM $BUILD_FROM

RUN apk add --no-cache \
      asterisk=18.2.1-r2 \
      asterisk-sample-config=18.2.1-r2

ENTRYPOINT [ "/s6-init" ]
CMD []
COPY root /
