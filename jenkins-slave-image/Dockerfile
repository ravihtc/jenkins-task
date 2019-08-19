FROM    jenkinsci/slave:alpine
USER    root 
RUN     addgroup -g 3000 docker && \
        apk add docker && \
        apk add git && \ 
        addgroup jenkins docker
USER    jenkins 
