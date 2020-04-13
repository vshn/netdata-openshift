FROM docker.io/netdata/netdata:v1.21.1

RUN \
    chgrp -R root /var/cache/netdata /var/lib/netdata /usr/libexec/netdata /usr/lib/netdata /usr/share/netdata && \
    chmod -R g+w,o+w /var/lib/netdata && \
    chmod -R g+x,o+x /usr/libexec/netdata
