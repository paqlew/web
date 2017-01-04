FROM golang

ADD . /go/src/
RUN go install .
ENTRYPOINT /go/bin/basic_web_server

EXPOSE 8080


