FROM python:alpine

RUN python --version

VOLUME ["/code"]
WORKDIR /code

# system packages
RUN apk --no-cache --update add \
    bash \
    curl \
    git \
    vim \
    gcc \
    python3-dev

RUN pip install --upgrade pip

# Shell entrypoint
 ENTRYPOINT [ "/bin/bash" ]