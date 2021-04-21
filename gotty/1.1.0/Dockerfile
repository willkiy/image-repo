FROM ubuntu:hirsute-20210401
MAINTAINER willkiy <willkiy@163.com>
COPY gotty /usr/bin/gotty
ENTRYPOINT ["bash","-c"]
CMD ["bash /usr/bin/gotty -p 9999 -w  --permit-arguments ssh"]