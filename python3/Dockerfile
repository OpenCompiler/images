FROM alpine:3.6
RUN apk add --no-cache coreutils gcc python3 musl-dev bash python3-dev
RUN pip3 install --upgrade pip 
RUN pip3 install numpy
ADD . /
