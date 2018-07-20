FROM alpine:3.6

RUN adduser -D nifi-operator
USER nifi-operator

ADD tmp/_output/bin/nifi-operator /usr/local/bin/nifi-operator
