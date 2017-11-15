FROM jakebailey/alpine-sane

RUN apk --no-cache add \
        emacs-nox \
    && adduser -D -s /bin/bash student

USER student
WORKDIR /home/student