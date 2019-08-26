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

# helpful pip packages
RUN pip install --upgrade pip && pip install \
    pytest

# Shell entrypoint
 ENTRYPOINT [ "/bin/bash" ]