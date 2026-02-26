FROM postgres:latest@sha256:a688ae5c99f86c1424e046ace0de890608cc0ddb5ec8ef72a6ff8305fdc8f4d2
COPY docker-healthcheck.sh /usr/local/bin/
HEALTHCHECK CMD ["docker-healthcheck.sh"]
