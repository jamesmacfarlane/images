FROM alpine:3.8

RUN apk update && apk add \
    bash \
    curl \
    jq \
    openssh-client \
    vim

ADD aliases.sh /etc/profile.d/aliases.sh

ENTRYPOINT ["/bin/bash"]
