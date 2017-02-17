FROM quay.io/coreos/clair:v1.2.2

ADD clair_config /config
RUN curl -sSL https://get.docker.com/ | sh
RUN go install -v github.com/coreos/clair/contrib/analyze-local-images
