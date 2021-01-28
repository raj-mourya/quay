FROM openshift/base-centos7

#Setup Go
RUN wget https://golang.org/dl/go1.15.7.linux-amd64.tar.gz && \
    tar -C /usr/local -xzf go1.15.7.linux-amd64.tar.gz && \
    
#Download the desired klar binary from the klar github site.
RUN go get github.com/optiopay/klar
CMD [“tail -f /dev/null”]
