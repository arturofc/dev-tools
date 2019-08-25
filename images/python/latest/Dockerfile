FROM python:alpine

RUN python --version

VOLUME ["/code"]
WORKDIR /code

# system packages
RUN apk --no-cache --update add \
    bash \
    curl \
    git \
    vim 

# helpful pip packages
RUN python -m pip install --upgrade pip && python -m pip install \
    pipenv \
    pytest

# install poetry: 

# Shell entrypoint
 ENTRYPOINT [ "/bin/bash" ]