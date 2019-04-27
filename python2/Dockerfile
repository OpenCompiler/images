FROM alpine:3.6
RUN apk add --no-cache coreutils gcc python python-dev py2-pip musl-dev bash
RUN pip install --upgrade pip
RUN pip install numpy
ADD . /
