FROM golang:1.25.4

ADD . /go/src/github.com/trainingbypackt/k8s-client-example
WORKDIR /go/src/github.com/trainingbypackt/k8s-client-example

RUN go build -v -o client

CMD ["/go/src/github.com/trainingbypackt/k8s-client-example/client"]

