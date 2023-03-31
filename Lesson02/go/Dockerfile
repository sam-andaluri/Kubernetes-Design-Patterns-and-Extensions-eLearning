FROM golang:1.19.7

ADD . /go/src/github.com/trainingbypackt/k8s-client-example
WORKDIR /go/src/github.com/trainingbypackt/k8s-client-example

RUN go build -v -o client

CMD ["/go/src/github.com/trainingbypackt/k8s-client-example/client"]

