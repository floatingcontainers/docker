FROM alpine:3.14

RUN apk add ansible==2.10.7-r0 \
            py3-jsonschema \
            py3-pip && \
    ansible-galaxy collection install ansible.utils
