FROM carello/todobackend-base:latest
MAINTAINER Chet Carello <chetcarello@gmail.com>

COPY target /wheelhouse

RUN . /appenv/bin/activate && \
    pip install --no-index -f /wheelhouse todobackend && \
    rm -rf /wheelhouse



