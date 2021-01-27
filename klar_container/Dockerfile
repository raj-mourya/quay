FROM centos7

#Setup Go
RUN wget https://golang.org/dl/go1.15.7.linux-amd64.tar.gz && \
    tar -C /usr/local -xzf go1.15.7.linux-amd64.tar.gz && \
    
#Download the desired klar binary form the klar github site.
RUN wget https://github.com/optiopay/klar/releases/download/v2.4.0/klar-2.4.0-linux-amd64

CMD [“tail -f /dev/null”]
