FROM alpine:3.16.0

ARG VERSION=3.5.1-r0

RUN apk --no-cache add ser2net=${VERSION}

CMD echo -n "Starting " && ser2net -v && ser2net -d -c /etc/ser2net.conf